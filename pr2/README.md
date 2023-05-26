# Сбор и аналитическая обработка информации о сетевом трафике

## Цель работы

1\. Развить практические навыки использования современного стека инструментов сбора и аналитической обработки информации о сетвом трафике

2\. Освоить базовые подходы блокировки нежелательного сетевого трафика

3\. Закрепить знания о современных сетевых протоколах прикладного уровня

## ️Исходные данные

1\. Компьютер с Windows 11 Pro

2\. WSL 2

3\. Сетевой анализатор - Wireshark

4\. Python 3.10.9

## ️Задание

1\. Собрать сетевой трафик (объемом не менее 100 Мб)

2\. Выделить метаинформацию сетевого трафика с помощью утилиты Zeek

3\. Собрать данные об источниках нежелательного трафика, например -- <https://github.com/StevenBlack>

4\. Написать программу на любом удобном языке (python, bash, R ...), котрая подсчитывает процент нежелательного трафика в собранном на этапе 1.

5\. Оформить отчет в соответствии с шаблоном

## Содержание ЛР

### Шаг 1

Собрать сетевой трафик (объемом не менее 100 Мб)

1\. Воспользоваться сетевым анализатором -- Wireshark

2\. Для формирования необходимого объема, после начала записи трафика посерфить Интернет: поискать в поисковых движках, полазить по новостям и т.д. Не рекомендуется формировать весь объем трафика за счет использования одним сервисом -- Telegram, Youtube, TikTok и пр. -- так как собранный сетевой профиль будет без характерных черт, которые можно будет затем отобразить и проанализировать на последующих этапах.


![photo_2023-04-13_07-40-03](https://user-images.githubusercontent.com/90779324/231707448-4d209673-e0ab-4276-afd6-50d23a804429.jpg)

### Шаг 2

Выделить метаинформацию сетевого трафика с помощью утилиты Zeek:

    zeek –C –r traffic.pcapng

Вычленить адреса из dns.log:

    awk '/\^\[\^#\]/ {print \$10}' dns.log \>\> dns

Полученные файлы:

![photo_2023-04-13_07-40-19](https://user-images.githubusercontent.com/90779324/231707597-95470897-99f2-4910-af50-be70fd229f4d.jpg)

### Шаг 3

Собрать данные об источниках нежелательного трафика, в данном случае с github -- <https://github.com/StevenBlack>

С репозитория взяты несколько файлов hosts и объединены в один с помощью команды cat hosts2 \>\> hosts

Извлечение адресов из hosts:

    cat hosts | cut -d " " -f2 >> hosts

### Шаг 4

Написать программу на языке Python 3.11.2, которая подсчитывает процент нежелательного трафика в собранном на этапе 1:

Код:

```{python3}
def main():
    with open('dns', 'r') as fdns, open('host_output', 'r') as fhosts:
        dns_l = []
        for line in fdns:
            line = line.strip()
            if line and line != "-":
                dns_l.append(line)
        
        hosts_l = []
        for line in fhosts:
            line = line.strip()
            if line and line != "-" and line != "#":
                hosts_l.append(line)

        dns_set = {x for x in dns_l}
        hosts_set = {x for x in hosts_l}

        common_lines = dns_set.intersection(hosts_set)

    print(f"Количество строк в файле с dns: {len(dns_l)}")
    print(f"Количество строк, которые есть в обоих файлах: {len(common_lines)}")
    print(f"Процент нежелательного трафика: {round(len(common_lines) / len(dns_l) * 100, 2)}%")

if __name__ == "__main__":
    main()
```

## ️Оценка результата

Собрано 122 Мб трафика.

Собрано данные об источниках нежелательного трафика.

Проведено их сравнение, найдены нежелательные dns адреса.

Подсчитан процент нежелательного трафика.

Получены результаты:

![photo_2023-04-13_07-40-25](https://user-images.githubusercontent.com/90779324/231707644-4874e5e8-458b-48b6-a42a-512de8d3ebe1.jpg)

## ️Вывод

В результате выполнения лабораторной работы были изучены инструменты сетевого анализа, извлечение необходимой информации о dns адресах с помощью Zeek, а также проведено сравнение и анализ нежелательного трафика.