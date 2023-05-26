<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en"><head>

<meta charset="utf-8">
<meta name="generator" content="quarto-1.2.335">

<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">


<title>Lab1</title>
<style>
code{white-space: pre-wrap;}
span.smallcaps{font-variant: small-caps;}
div.columns{display: flex; gap: min(4vw, 1.5em);}
div.column{flex: auto; overflow-x: auto;}
div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
ul.task-list{list-style: none;}
ul.task-list li input[type="checkbox"] {
  width: 0.8em;
  margin: 0 0.8em 0.2em -1.6em;
  vertical-align: middle;
}
pre > code.sourceCode { white-space: pre; position: relative; }
pre > code.sourceCode > span { display: inline-block; line-height: 1.25; }
pre > code.sourceCode > span:empty { height: 1.2em; }
.sourceCode { overflow: visible; }
code.sourceCode > span { color: inherit; text-decoration: inherit; }
div.sourceCode { margin: 1em 0; }
pre.sourceCode { margin: 0; }
@media screen {
div.sourceCode { overflow: auto; }
}
@media print {
pre > code.sourceCode { white-space: pre-wrap; }
pre > code.sourceCode > span { text-indent: -5em; padding-left: 5em; }
}
pre.numberSource code
  { counter-reset: source-line 0; }
pre.numberSource code > span
  { position: relative; left: -4em; counter-increment: source-line; }
pre.numberSource code > span > a:first-child::before
  { content: counter(source-line);
    position: relative; left: -1em; text-align: right; vertical-align: baseline;
    border: none; display: inline-block;
    -webkit-touch-callout: none; -webkit-user-select: none;
    -khtml-user-select: none; -moz-user-select: none;
    -ms-user-select: none; user-select: none;
    padding: 0 4px; width: 4em;
    color: #aaaaaa;
  }
pre.numberSource { margin-left: 3em; border-left: 1px solid #aaaaaa;  padding-left: 4px; }
div.sourceCode
  {   }
@media screen {
pre > code.sourceCode > span > a:first-child::before { text-decoration: underline; }
}
code span.al { color: #ff0000; font-weight: bold; } /* Alert */
code span.an { color: #60a0b0; font-weight: bold; font-style: italic; } /* Annotation */
code span.at { color: #7d9029; } /* Attribute */
code span.bn { color: #40a070; } /* BaseN */
code span.bu { color: #008000; } /* BuiltIn */
code span.cf { color: #007020; font-weight: bold; } /* ControlFlow */
code span.ch { color: #4070a0; } /* Char */
code span.cn { color: #880000; } /* Constant */
code span.co { color: #60a0b0; font-style: italic; } /* Comment */
code span.cv { color: #60a0b0; font-weight: bold; font-style: italic; } /* CommentVar */
code span.do { color: #ba2121; font-style: italic; } /* Documentation */
code span.dt { color: #902000; } /* DataType */
code span.dv { color: #40a070; } /* DecVal */
code span.er { color: #ff0000; font-weight: bold; } /* Error */
code span.ex { } /* Extension */
code span.fl { color: #40a070; } /* Float */
code span.fu { color: #06287e; } /* Function */
code span.im { color: #008000; font-weight: bold; } /* Import */
code span.in { color: #60a0b0; font-weight: bold; font-style: italic; } /* Information */
code span.kw { color: #007020; font-weight: bold; } /* Keyword */
code span.op { color: #666666; } /* Operator */
code span.ot { color: #007020; } /* Other */
code span.pp { color: #bc7a00; } /* Preprocessor */
code span.sc { color: #4070a0; } /* SpecialChar */
code span.ss { color: #bb6688; } /* SpecialString */
code span.st { color: #4070a0; } /* String */
code span.va { color: #19177c; } /* Variable */
code span.vs { color: #4070a0; } /* VerbatimString */
code span.wa { color: #60a0b0; font-weight: bold; font-style: italic; } /* Warning */
</style>


<script src="pr1_files/libs/clipboard/clipboard.min.js"></script>
<script src="pr1_files/libs/quarto-html/quarto.js"></script>
<script src="pr1_files/libs/quarto-html/popper.min.js"></script>
<script src="pr1_files/libs/quarto-html/tippy.umd.min.js"></script>
<script src="pr1_files/libs/quarto-html/anchor.min.js"></script>
<link href="pr1_files/libs/quarto-html/tippy.css" rel="stylesheet">
<link href="pr1_files/libs/quarto-html/quarto-syntax-highlighting.css" rel="stylesheet" id="quarto-text-highlighting-styles">
<script src="pr1_files/libs/bootstrap/bootstrap.min.js"></script>
<link href="pr1_files/libs/bootstrap/bootstrap-icons.css" rel="stylesheet">
<link href="pr1_files/libs/bootstrap/bootstrap.min.css" rel="stylesheet" id="quarto-bootstrap" data-mode="light">


</head>

<body class="fullcontent">

<div id="quarto-content" class="page-columns page-rows-contents page-layout-article">

<main class="content" id="quarto-document-content">

<header id="title-block-header" class="quarto-title-block default">
<div class="quarto-title">
<h1 class="title">Lab1</h1>
</div>



<div class="quarto-title-meta">

    
  
    
  </div>
  

</header>

<section id="системы-аутентификации-и-защиты-от-несанкционированного-доступа" class="level1">
<h1>Системы аутентификации и защиты от несанкционированного доступа</h1>
<p>Лабораторная работа №1</p>
<section id="цель" class="level2">
<h2 class="anchored" data-anchor-id="цель">Цель</h2>
<p>Вывести информацию о системе</p>
</section>
<section id="исходные-данные" class="level2">
<h2 class="anchored" data-anchor-id="исходные-данные">Исходные данные</h2>
<ol type="1">
<li>ОС Windows 10</li>
<li>RStudio Desktop</li>
<li>Интерпретатор языка R 4.2.2</li>
</ol>
</section>
<section id="план" class="level2">
<h2 class="anchored" data-anchor-id="план">План</h2>
<ol type="1">
<li>Выполнить команду system2(“systeminfo”, stdout = TRUE)</li>
<li>Выполнить команду system(“wmic cpu get name”)</li>
<li>Выполнить команду system(“powershell.exe Get-EventLog -LogName System -Newest 30”)</li>
</ol>
</section>
<section id="шаги" class="level2">
<h2 class="anchored" data-anchor-id="шаги">Шаги</h2>
<ol type="1">
<li>Сначала выполним команду system2(“systeminfo”, stdout = TRUE) для вывода информации о системе</li>
</ol>
<div class="cell">
<div class="sourceCode cell-code" id="cb1"><pre class="sourceCode r code-with-copy"><code class="sourceCode r"><span id="cb1-1"><a href="#cb1-1" aria-hidden="true" tabindex="-1"></a><span class="fu">system2</span>(<span class="st">"systeminfo"</span>, <span class="at">stdout =</span> <span class="cn">TRUE</span>)</span></code><button title="Copy to Clipboard" class="code-copy-button"><i class="bi"></i></button></pre></div>
<div class="cell-output cell-output-stdout">
<pre><code> [1] ""                                                                                                               
 [2] "Host Name:                 LAPTOP-7AOQHG98"                                                                     
 [3] "OS Name:                   Microsoft Windows 10 Home Single Language"                                           
 [4] "OS Version:                10.0.19045 N/A Build 19045"                                                          
 [5] "OS Manufacturer:           Microsoft Corporation"                                                               
 [6] "OS Configuration:          Standalone Workstation"                                                              
 [7] "OS Build Type:             Multiprocessor Free"                                                                 
 [8] "Registered Owner:          MagicBook"                                                                           
 [9] "Registered Organization:   N/A"                                                                                 
[10] "Product ID:                00342-41326-93163-AAOEM"                                                             
[11] "Original Install Date:     26.06.2021, 17:49:51"                                                                
[12] "System Boot Time:          25.05.2023, 15:50:05"                                                                
[13] "System Manufacturer:       HUAWEI"                                                                              
[14] "System Model:              BOHK-WAX9X"                                                                          
[15] "System Type:               x64-based PC"                                                                        
[16] "Processor(s):              1 Processor(s) Installed."                                                           
[17] "                           [01]: AMD64 Family 23 Model 24 Stepping 1 AuthenticAMD ~2100 Mhz"                    
[18] "BIOS Version:              HUAWEI 1.06, 11.03.2020"                                                             
[19] "Windows Directory:         C:\\WINDOWS"                                                                         
[20] "System Directory:          C:\\WINDOWS\\system32"                                                               
[21] "Boot Device:               \\Device\\HarddiskVolume1"                                                           
[22] "System Locale:             ru;Russian"                                                                          
[23] "Input Locale:              ru;Russian"                                                                          
[24] "Time Zone:                 (UTC+03:00) Moscow, St. Petersburg"                                                  
[25] "Total Physical Memory:     7&nbsp;104 MB"                                                                            
[26] "Available Physical Memory: 612 MB"                                                                              
[27] "Virtual Memory: Max Size:  17&nbsp;400 MB"                                                                           
[28] "Virtual Memory: Available: 2&nbsp;641 MB"                                                                            
[29] "Virtual Memory: In Use:    14&nbsp;759 MB"                                                                           
[30] "Page File Location(s):     D:\\pagefile.sys"                                                                    
[31] "Domain:                    WORKGROUP"                                                                           
[32] "Logon Server:              \\\\LAPTOP-7AOQHG98"                                                                 
[33] "Hotfix(s):                 21 Hotfix(s) Installed."                                                             
[34] "                           [01]: KB5022502"                                                                     
[35] "                           [02]: KB4562830"                                                                     
[36] "                           [03]: KB4570334"                                                                     
[37] "                           [04]: KB4580325"                                                                     
[38] "                           [05]: KB4586864"                                                                     
[39] "                           [06]: KB5003791"                                                                     
[40] "                           [07]: KB5012170"                                                                     
[41] "                           [08]: KB5015684"                                                                     
[42] "                           [09]: KB5026361"                                                                     
[43] "                           [10]: KB5006753"                                                                     
[44] "                           [11]: KB5007273"                                                                     
[45] "                           [12]: KB5011352"                                                                     
[46] "                           [13]: KB5014035"                                                                     
[47] "                           [14]: KB5014671"                                                                     
[48] "                           [15]: KB5015895"                                                                     
[49] "                           [16]: KB5016705"                                                                     
[50] "                           [17]: KB5018506"                                                                     
[51] "                           [18]: KB5020372"                                                                     
[52] "                           [19]: KB5022924"                                                                     
[53] "                           [20]: KB5025315"                                                                     
[54] "                           [21]: KB5005699"                                                                     
[55] "Network Card(s):           2 NIC(s) Installed."                                                                 
[56] "                           [01]: Realtek 8822CE Wireless LAN 802.11ac PCI-E NIC"                                
[57] "                                 Connection Name: Беспроводная сеть"                                            
[58] "                                 DHCP Enabled:    Yes"                                                          
[59] "                                 DHCP Server:     192.168.1.1"                                                  
[60] "                                 IP address(es)"                                                                
[61] "                                 [01]: 192.168.1.3"                                                             
[62] "                                 [02]: fe80::f8c3:2217:78d0:c087"                                               
[63] "                           [02]: Kaspersky VPN"                                                                 
[64] "                                 Connection Name: Подключение по локальной сети"                                
[65] "                                 Status:          Media disconnected"                                           
[66] "Hyper-V Requirements:      A hypervisor has been detected. Features required for Hyper-V will not be displayed."</code></pre>
</div>
</div>
<p>2. Далее команда system(“wmic cpu get name”) для вывода информации о процессоре</p>
<div class="cell">
<div class="sourceCode cell-code" id="cb3"><pre class="sourceCode r code-with-copy"><code class="sourceCode r"><span id="cb3-1"><a href="#cb3-1" aria-hidden="true" tabindex="-1"></a><span class="fu">system2</span>(<span class="st">"cmd"</span>, <span class="at">args =</span> <span class="fu">c</span>(<span class="st">"/c"</span>, <span class="st">"wmic cpu get name"</span>), <span class="at">stdout =</span> <span class="cn">TRUE</span>)</span></code><button title="Copy to Clipboard" class="code-copy-button"><i class="bi"></i></button></pre></div>
<div class="cell-output cell-output-stdout">
<pre><code>[1] "Name                                           \r"
[2] "AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  \r"
[3] "\r"                                               </code></pre>
</div>
</div>
<p>3. Также выполним команду system(“powershell.exe Get-EventLog -LogName System -Newest 30”) для вывода логов</p>
<div class="cell">
<div class="sourceCode cell-code" id="cb5"><pre class="sourceCode r code-with-copy"><code class="sourceCode r"><span id="cb5-1"><a href="#cb5-1" aria-hidden="true" tabindex="-1"></a><span class="fu">system2</span>(<span class="st">"powershell.exe"</span>, <span class="at">args =</span> <span class="fu">c</span>(<span class="st">"Get-EventLog"</span>, <span class="st">"-LogName"</span>, <span class="st">"System"</span>, <span class="st">"-Newest"</span>, <span class="st">"30"</span>), <span class="at">stdout =</span> <span class="cn">TRUE</span>)</span></code><button title="Copy to Clipboard" class="code-copy-button"><i class="bi"></i></button></pre></div>
<div class="cell-output cell-output-stdout">
<pre><code> [1] ""                                                                                                                       
 [2] "   Index Time          EntryType   Source                 InstanceID Message                                           "
 [3] "   ----- ----          ---------   ------                 ---------- -------                                           "
 [4] "   30227 май 26 20:28  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
 [5] "   30226 май 26 20:24  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
 [6] "   30225 май 26 18:26  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
 [7] "   30224 май 26 17:14  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
 [8] "   30223 май 26 14:59  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
 [9] "   30222 май 26 14:57  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[10] "   30221 май 26 13:55  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[11] "   30220 май 26 13:53  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[12] "   30219 май 26 13:27  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[13] "   30218 май 26 13:25  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[14] "   30217 май 26 13:15  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[15] "   30216 май 26 13:14  Information Microsoft-Windows...           44 Windows Update started downloading an update.     "
[16] "   30215 май 26 13:13  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[17] "   30214 май 26 12:00  Information EventLog               2147489661 The system uptime is 72595 seconds.               "
[18] "   30213 май 26 11:56  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[19] "   30212 май 26 11:56  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[20] "   30211 май 26 11:52  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[21] "   30210 май 26 11:52  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[22] "   30209 май 26 11:44  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[23] "   30208 май 26 11:43  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[24] "   30207 май 26 11:27  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[25] "   30206 май 26 11:25  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[26] "   30205 май 26 11:24  Information Service Control M...   1073748864 The start type of the Фоновая интеллектуальная ..."
[27] "   30204 май 26 11:23  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[28] "   30203 май 26 11:23  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[29] "   30202 май 26 11:22  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[30] "   30201 май 26 11:21  Information Microsoft-Windows...           16 The description for Event ID '16' in Source 'Mi..."
[31] "   30200 май 26 11:21  Information Microsoft-Windows...          105 The description for Event ID '105' in Source 'M..."
[32] "   30199 май 26 11:18  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[33] "   30198 май 26 11:00  Warning     DCOM                        10016 The description for Event ID '10016' in Source ..."
[34] ""                                                                                                                       
[35] ""                                                                                                                       </code></pre>
</div>
</div>
</section>
<section id="оценка-результата" class="level2">
<h2 class="anchored" data-anchor-id="оценка-результата">Оценка результата</h2>
<p>В результате лабораторной работы мы получили основную информацию об ОС, процессоре и логи системы.</p>
</section>
<section id="вывод" class="level2">
<h2 class="anchored" data-anchor-id="вывод">Вывод</h2>
<p>Таким образом, мы научились работать с базовыми командами командой строки и получать информацию об операционной системе.</p>
</section>
</section>

</main>
<!-- /main column -->
<script id="quarto-html-after-body" type="application/javascript">
window.document.addEventListener("DOMContentLoaded", function (event) {
  const toggleBodyColorMode = (bsSheetEl) => {
    const mode = bsSheetEl.getAttribute("data-mode");
    const bodyEl = window.document.querySelector("body");
    if (mode === "dark") {
      bodyEl.classList.add("quarto-dark");
      bodyEl.classList.remove("quarto-light");
    } else {
      bodyEl.classList.add("quarto-light");
      bodyEl.classList.remove("quarto-dark");
    }
  }
  const toggleBodyColorPrimary = () => {
    const bsSheetEl = window.document.querySelector("link#quarto-bootstrap");
    if (bsSheetEl) {
      toggleBodyColorMode(bsSheetEl);
    }
  }
  toggleBodyColorPrimary();  
  const icon = "";
  const anchorJS = new window.AnchorJS();
  anchorJS.options = {
    placement: 'right',
    icon: icon
  };
  anchorJS.add('.anchored');
  const clipboard = new window.ClipboardJS('.code-copy-button', {
    target: function(trigger) {
      return trigger.previousElementSibling;
    }
  });
  clipboard.on('success', function(e) {
    // button target
    const button = e.trigger;
    // don't keep focus
    button.blur();
    // flash "checked"
    button.classList.add('code-copy-button-checked');
    var currentTitle = button.getAttribute("title");
    button.setAttribute("title", "Copied!");
    let tooltip;
    if (window.bootstrap) {
      button.setAttribute("data-bs-toggle", "tooltip");
      button.setAttribute("data-bs-placement", "left");
      button.setAttribute("data-bs-title", "Copied!");
      tooltip = new bootstrap.Tooltip(button, 
        { trigger: "manual", 
          customClass: "code-copy-button-tooltip",
          offset: [0, -8]});
      tooltip.show();    
    }
    setTimeout(function() {
      if (tooltip) {
        tooltip.hide();
        button.removeAttribute("data-bs-title");
        button.removeAttribute("data-bs-toggle");
        button.removeAttribute("data-bs-placement");
      }
      button.setAttribute("title", currentTitle);
      button.classList.remove('code-copy-button-checked');
    }, 1000);
    // clear code selection
    e.clearSelection();
  });
  function tippyHover(el, contentFn) {
    const config = {
      allowHTML: true,
      content: contentFn,
      maxWidth: 500,
      delay: 100,
      arrow: false,
      appendTo: function(el) {
          return el.parentElement;
      },
      interactive: true,
      interactiveBorder: 10,
      theme: 'quarto',
      placement: 'bottom-start'
    };
    window.tippy(el, config); 
  }
  const noterefs = window.document.querySelectorAll('a[role="doc-noteref"]');
  for (var i=0; i<noterefs.length; i++) {
    const ref = noterefs[i];
    tippyHover(ref, function() {
      // use id or data attribute instead here
      let href = ref.getAttribute('data-footnote-href') || ref.getAttribute('href');
      try { href = new URL(href).hash; } catch {}
      const id = href.replace(/^#\/?/, "");
      const note = window.document.getElementById(id);
      return note.innerHTML;
    });
  }
  const findCites = (el) => {
    const parentEl = el.parentElement;
    if (parentEl) {
      const cites = parentEl.dataset.cites;
      if (cites) {
        return {
          el,
          cites: cites.split(' ')
        };
      } else {
        return findCites(el.parentElement)
      }
    } else {
      return undefined;
    }
  };
  var bibliorefs = window.document.querySelectorAll('a[role="doc-biblioref"]');
  for (var i=0; i<bibliorefs.length; i++) {
    const ref = bibliorefs[i];
    const citeInfo = findCites(ref);
    if (citeInfo) {
      tippyHover(citeInfo.el, function() {
        var popup = window.document.createElement('div');
        citeInfo.cites.forEach(function(cite) {
          var citeDiv = window.document.createElement('div');
          citeDiv.classList.add('hanging-indent');
          citeDiv.classList.add('csl-entry');
          var biblioDiv = window.document.getElementById('ref-' + cite);
          if (biblioDiv) {
            citeDiv.innerHTML = biblioDiv.innerHTML;
          }
          popup.appendChild(citeDiv);
        });
        return popup.innerHTML;
      });
    }
  }
});
</script>
</div> <!-- /content -->



</body></html>