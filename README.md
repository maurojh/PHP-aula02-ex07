<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<!-- 2019-08-13 ter 18:53 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>&lrm;</title>
<meta name="generator" content="Org mode" />
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  .title  { text-align: center;
             margin-bottom: .2em; }
  .subtitle { text-align: center;
              font-size: medium;
              font-weight: bold;
              margin-top:0; }
  .todo   { font-family: monospace; color: red; }
  .done   { font-family: monospace; color: green; }
  .priority { font-family: monospace; color: orange; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .org-right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .org-left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .org-center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  /* Languages per Org manual */
  pre.src-asymptote:before { content: 'Asymptote'; }
  pre.src-awk:before { content: 'Awk'; }
  pre.src-C:before { content: 'C'; }
  /* pre.src-C++ doesn't work in CSS */
  pre.src-clojure:before { content: 'Clojure'; }
  pre.src-css:before { content: 'CSS'; }
  pre.src-D:before { content: 'D'; }
  pre.src-ditaa:before { content: 'ditaa'; }
  pre.src-dot:before { content: 'Graphviz'; }
  pre.src-calc:before { content: 'Emacs Calc'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-fortran:before { content: 'Fortran'; }
  pre.src-gnuplot:before { content: 'gnuplot'; }
  pre.src-haskell:before { content: 'Haskell'; }
  pre.src-hledger:before { content: 'hledger'; }
  pre.src-java:before { content: 'Java'; }
  pre.src-js:before { content: 'Javascript'; }
  pre.src-latex:before { content: 'LaTeX'; }
  pre.src-ledger:before { content: 'Ledger'; }
  pre.src-lisp:before { content: 'Lisp'; }
  pre.src-lilypond:before { content: 'Lilypond'; }
  pre.src-lua:before { content: 'Lua'; }
  pre.src-matlab:before { content: 'MATLAB'; }
  pre.src-mscgen:before { content: 'Mscgen'; }
  pre.src-ocaml:before { content: 'Objective Caml'; }
  pre.src-octave:before { content: 'Octave'; }
  pre.src-org:before { content: 'Org mode'; }
  pre.src-oz:before { content: 'OZ'; }
  pre.src-plantuml:before { content: 'Plantuml'; }
  pre.src-processing:before { content: 'Processing.js'; }
  pre.src-python:before { content: 'Python'; }
  pre.src-R:before { content: 'R'; }
  pre.src-ruby:before { content: 'Ruby'; }
  pre.src-sass:before { content: 'Sass'; }
  pre.src-scheme:before { content: 'Scheme'; }
  pre.src-screen:before { content: 'Gnu Screen'; }
  pre.src-sed:before { content: 'Sed'; }
  pre.src-sh:before { content: 'shell'; }
  pre.src-sql:before { content: 'SQL'; }
  pre.src-sqlite:before { content: 'SQLite'; }
  /* additional languages in org.el's org-babel-load-languages alist */
  pre.src-forth:before { content: 'Forth'; }
  pre.src-io:before { content: 'IO'; }
  pre.src-J:before { content: 'J'; }
  pre.src-makefile:before { content: 'Makefile'; }
  pre.src-maxima:before { content: 'Maxima'; }
  pre.src-perl:before { content: 'Perl'; }
  pre.src-picolisp:before { content: 'Pico Lisp'; }
  pre.src-scala:before { content: 'Scala'; }
  pre.src-shell:before { content: 'Shell Script'; }
  pre.src-ebnf2ps:before { content: 'ebfn2ps'; }
  /* additional language identifiers per "defun org-babel-execute"
       in ob-*.el */
  pre.src-cpp:before  { content: 'C++'; }
  pre.src-abc:before  { content: 'ABC'; }
  pre.src-coq:before  { content: 'Coq'; }
  pre.src-groovy:before  { content: 'Groovy'; }
  /* additional language identifiers from org-babel-shell-names in
     ob-shell.el: ob-shell is the only babel language using a lambda to put
     the execution function name together. */
  pre.src-bash:before  { content: 'bash'; }
  pre.src-csh:before  { content: 'csh'; }
  pre.src-ash:before  { content: 'ash'; }
  pre.src-dash:before  { content: 'dash'; }
  pre.src-ksh:before  { content: 'ksh'; }
  pre.src-mksh:before  { content: 'mksh'; }
  pre.src-posh:before  { content: 'posh'; }
  /* Additional Emacs modes also supported by the LaTeX listings package */
  pre.src-ada:before { content: 'Ada'; }
  pre.src-asm:before { content: 'Assembler'; }
  pre.src-caml:before { content: 'Caml'; }
  pre.src-delphi:before { content: 'Delphi'; }
  pre.src-html:before { content: 'HTML'; }
  pre.src-idl:before { content: 'IDL'; }
  pre.src-mercury:before { content: 'Mercury'; }
  pre.src-metapost:before { content: 'MetaPost'; }
  pre.src-modula-2:before { content: 'Modula-2'; }
  pre.src-pascal:before { content: 'Pascal'; }
  pre.src-ps:before { content: 'PostScript'; }
  pre.src-prolog:before { content: 'Prolog'; }
  pre.src-simula:before { content: 'Simula'; }
  pre.src-tcl:before { content: 'tcl'; }
  pre.src-tex:before { content: 'TeX'; }
  pre.src-plain-tex:before { content: 'Plain TeX'; }
  pre.src-verilog:before { content: 'Verilog'; }
  pre.src-vhdl:before { content: 'VHDL'; }
  pre.src-xml:before { content: 'XML'; }
  pre.src-nxml:before { content: 'XML'; }
  /* add a generic configuration mode; LaTeX export needs an additional
     (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs */
  pre.src-conf:before { content: 'Configuration File'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.org-right  { text-align: center;  }
  th.org-left   { text-align: center;   }
  th.org-center { text-align: center; }
  td.org-right  { text-align: right;  }
  td.org-left   { text-align: left;   }
  td.org-center { text-align: center; }
  dt { font-weight: bold; }
  .footpara { display: inline; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  .org-svg { width: 90%; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#org50d860e">1. Operadores em PHP</a>
<ul>
<li><a href="#org1eb8c29">1.1. Aritmética:</a></li>
<li><a href="#org4a5458b">1.2. Exercício 1</a></li>
<li><a href="#orgb126e1b">1.3. Exercício 2</a></li>
<li><a href="#org0fc2611">1.4. Atribuição</a></li>
<li><a href="#org60173b9">1.5. Exercício 3</a></li>
<li><a href="#orgae0e5fe">1.6. Comparação</a></li>
<li><a href="#org64b98c0">1.7. Exercício 4</a></li>
<li><a href="#org7b85f5c">1.8. Incremento</a></li>
<li><a href="#org55eda73">1.9. Exercício 5</a></li>
<li><a href="#org99cd686">1.10. Decremento</a></li>
<li><a href="#org45b5099">1.11. Exercício 6</a></li>
<li><a href="#org6a6b5c1">1.12. Lógica</a></li>
<li><a href="#orgf266323">1.13. Exercício 7</a></li>
</ul>
</li>
</ul>
</div>
</div>

<div id="outline-container-org50d860e" class="outline-2">
<h2 id="org50d860e"><span class="section-number-2">1</span> Operadores em PHP</h2>
<div class="outline-text-2" id="text-1">
</div>
<div id="outline-container-org1eb8c29" class="outline-3">
<h3 id="org1eb8c29"><span class="section-number-3">1.1</span> Aritmética:</h3>
<div class="outline-text-3" id="text-1-1">
<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Operador</th>
<th scope="col" class="org-left">Operação</th>
<th scope="col" class="org-left">Exemplo</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-left">+</td>
<td class="org-left">Adição</td>
<td class="org-left">$x + 2</td>
</tr>

<tr>
<td class="org-left">-</td>
<td class="org-left">Subtração</td>
<td class="org-left">$x - 4</td>
</tr>

<tr>
<td class="org-left">*</td>
<td class="org-left">Multiplicação</td>
<td class="org-left">2 * $x</td>
</tr>

<tr>
<td class="org-left">%</td>
<td class="org-left">Resto da divisão</td>
<td class="org-left">$x % 2</td>
</tr>

<tr>
<td class="org-left">**</td>
<td class="org-left">Exponenciação</td>
<td class="org-left">$x ** 3</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-org4a5458b" class="outline-3">
<h3 id="org4a5458b"><span class="section-number-3">1.2</span> Exercício 1</h3>
<div class="outline-text-3" id="text-1-2">
<p>
Crie uma página que recebe um número e verifique se o número é par ou ímpar, 
sabendo que o resto da divisão de um número par por 2 é 0.
</p>

<pre class="example">
$resto = 3 % 2; 
echo $resto;   //  imprime 1

$resto = 4 % 2;
echo $resto;    // imprime 0
</pre>
</div>
</div>

<div id="outline-container-orgb126e1b" class="outline-3">
<h3 id="orgb126e1b"><span class="section-number-3">1.3</span> Exercício 2</h3>
<div class="outline-text-3" id="text-1-3">
<p>
A função rand(), gera um inteiro aleatório. No exemplo abaixo, o valor de $x poderá ser 1, 2 ou 3.
</p>

<pre class="example">
$x = rand(1, 3);
</pre>

<p>
Altere a página a02ex01.php de maneira a exibir a imagem de dois dados aleatoriamente. Efetue a soma dos valores e exiba uma mensagem de acordo com a tabela abaixo:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-right">Soma</th>
<th scope="col" class="org-left">Mensagem</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-right">10</td>
<td class="org-left">Ganhou 5 Pontos</td>
</tr>

<tr>
<td class="org-right">7</td>
<td class="org-left">Ganhou 7 Pontos</td>
</tr>

<tr>
<td class="org-right">5</td>
<td class="org-left">Ganhou 9 Pontos</td>
</tr>

<tr>
<td class="org-right">3</td>
<td class="org-left">Ganhou 11 Pontos</td>
</tr>

<tr>
<td class="org-right">2,4,6,8,9,11 ou 12</td>
<td class="org-left">Perdeu</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-org0fc2611" class="outline-3">
<h3 id="org0fc2611"><span class="section-number-3">1.4</span> Atribuição</h3>
<div class="outline-text-3" id="text-1-4">
<p>
Para atribuir um valor numérico à uma variável podemos usar:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Operador</th>
<th scope="col" class="org-left">Exemplo</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-left">=</td>
<td class="org-left">$x = 2;</td>
</tr>

<tr>
<td class="org-left">+=</td>
<td class="org-left">$x += 3;</td>
</tr>

<tr>
<td class="org-left">-=</td>
<td class="org-left">$x -= 2;</td>
</tr>

<tr>
<td class="org-left">*=</td>
<td class="org-left">$x *= 3;</td>
</tr>

<tr>
<td class="org-left">/=</td>
<td class="org-left">$x /= 2;</td>
</tr>

<tr>
<td class="org-left">%=</td>
<td class="org-left">$x %= 2;</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-org60173b9" class="outline-3">
<h3 id="org60173b9"><span class="section-number-3">1.5</span> Exercício 3</h3>
<div class="outline-text-3" id="text-1-5">
<p>
Utilize os operadores de atribuição na página a02ex03.php.
</p>
</div>
</div>

<div id="outline-container-orgae0e5fe" class="outline-3">
<h3 id="orgae0e5fe"><span class="section-number-3">1.6</span> Comparação</h3>
<div class="outline-text-3" id="text-1-6">
<p>
Podemos comparar dois números ou strings com:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Operador</th>
<th scope="col" class="org-left">Exemplo</th>
<th scope="col" class="org-left">Retorno</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-left">==</td>
<td class="org-left">$x == $y</td>
<td class="org-left">true se x for igual à y</td>
</tr>

<tr>
<td class="org-left"><code>=</code></td>
<td class="org-left">$x <code>=</code> $y</td>
<td class="org-left">true se x for igual à y e tiver o mesmo tipo</td>
</tr>

<tr>
<td class="org-left">!=</td>
<td class="org-left">$x != $y</td>
<td class="org-left">true se x não for igual à y</td>
</tr>

<tr>
<td class="org-left">&lt;&gt;</td>
<td class="org-left">$x &lt;&gt; $y</td>
<td class="org-left">true se x for diferente de y</td>
</tr>

<tr>
<td class="org-left">!==</td>
<td class="org-left">$x !== $y</td>
<td class="org-left">true se x for diferente de y ou não tiver o mesmo tipo</td>
</tr>

<tr>
<td class="org-left">&gt;</td>
<td class="org-left">$x &gt; $y</td>
<td class="org-left">true se x for maior que y</td>
</tr>

<tr>
<td class="org-left">&lt;</td>
<td class="org-left">$x &lt; $y</td>
<td class="org-left">true se x for menor que y</td>
</tr>

<tr>
<td class="org-left">&gt;=</td>
<td class="org-left">$x &gt;= $y</td>
<td class="org-left">true se x for maior ou igual à y</td>
</tr>

<tr>
<td class="org-left">&lt;=</td>
<td class="org-left">$x &lt;= $y</td>
<td class="org-left">true se x for menor ou igual à y</td>
</tr>

<tr>
<td class="org-left">&lt;=&gt;</td>
<td class="org-left">$x &lt;=&gt; $y</td>
<td class="org-left">-1 se x for menor que y, 0 se x for igual à y e 1 se x for maior que y</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-org64b98c0" class="outline-3">
<h3 id="org64b98c0"><span class="section-number-3">1.7</span> Exercício 4</h3>
<div class="outline-text-3" id="text-1-7">
<p>
Utilizando a página a02ex04.php implemente a página recebe_a02ex04.php que recebe os números digitados pelo usuário e exibe o resultado de cada um dos operadores de comparação.
</p>
</div>
</div>

<div id="outline-container-org7b85f5c" class="outline-3">
<h3 id="org7b85f5c"><span class="section-number-3">1.8</span> Incremento</h3>
<div class="outline-text-3" id="text-1-8">
<p>
Podemos aumentar em 1 o valor de uma variável com os operadores:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Operador</th>
<th scope="col" class="org-left">Exemplo</th>
<th scope="col" class="org-left">Resultado</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-left">++</td>
<td class="org-left">++$x</td>
<td class="org-left">Aumenta o valor de x e depois retorna o valor de x</td>
</tr>

<tr>
<td class="org-left">++</td>
<td class="org-left">$x++</td>
<td class="org-left">Retorna o valor de x e depois aumenta o valor de x</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-org55eda73" class="outline-3">
<h3 id="org55eda73"><span class="section-number-3">1.9</span> Exercício 5</h3>
<div class="outline-text-3" id="text-1-9">
<p>
Crie uma página que recebe um número e aumenta o valor utilizando os dois operadores de incremento.
</p>
</div>
</div>

<div id="outline-container-org99cd686" class="outline-3">
<h3 id="org99cd686"><span class="section-number-3">1.10</span> Decremento</h3>
<div class="outline-text-3" id="text-1-10">
<p>
Podemos reduzir em 1 o valor de uma variável com os operadores:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Operador</th>
<th scope="col" class="org-left">Exemplo</th>
<th scope="col" class="org-left">Resultado</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-left">--</td>
<td class="org-left">&#x2013;$x</td>
<td class="org-left">Reduz o valor de x e depois retorna o valor de x</td>
</tr>

<tr>
<td class="org-left">--</td>
<td class="org-left">$x--</td>
<td class="org-left">Retorna o valor de x e depois reduz o valor de x</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-org45b5099" class="outline-3">
<h3 id="org45b5099"><span class="section-number-3">1.11</span> Exercício 6</h3>
<div class="outline-text-3" id="text-1-11">
<p>
Crie uma página que recebe um número e diminui o valor utilizando os dois operadores de decremento.
</p>
</div>
</div>

<div id="outline-container-org6a6b5c1" class="outline-3">
<h3 id="org6a6b5c1"><span class="section-number-3">1.12</span> Lógica</h3>
<div class="outline-text-3" id="text-1-12">
<p>
Condições podem ser combinadas utilizando os operadores lógicos:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<tbody>
<tr>
<td class="org-left">Operador</td>
<td class="org-left">Exemplo</td>
<td class="org-left">Resultado</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>

<tr>
<td class="org-left">and</td>
<td class="org-left">$x and $y</td>
<td class="org-left">true se x e y forem true</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>

<tr>
<td class="org-left">or</td>
<td class="org-left">$x or $y</td>
<td class="org-left">true se x ou y forem true</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>

<tr>
<td class="org-left">xor</td>
<td class="org-left">$x xor $y</td>
<td class="org-left">true se x ou y forem true, mas não ambos</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>

<tr>
<td class="org-left">&amp;&amp;</td>
<td class="org-left">$x &amp;&amp; $y</td>
<td class="org-left">true se x e y forem true</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>

<tr>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">$x</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">$y</td>
<td class="org-left">true se x ou y forem true</td>
</tr>

<tr>
<td class="org-left">!</td>
<td class="org-left">!$x</td>
<td class="org-left">true se x for false</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-orgf266323" class="outline-3">
<h3 id="orgf266323"><span class="section-number-3">1.13</span> Exercício 7</h3>
<div class="outline-text-3" id="text-1-13">
<p>
Crie uma página que calcula o preço de um ingresso para uma festa:
</p>

<p>
Ingresso:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />

<col  class="org-right" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-right">homem</th>
<th scope="col" class="org-right">mulher</th>
</tr>
</thead>
<tbody>
<tr>
<td class="org-right">20</td>
<td class="org-right">15</td>
</tr>
</tbody>
</table>

<p>
Adicional:
</p>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />
</colgroup>
<tbody>
<tr>
<td class="org-right">Menor de 40</td>
</tr>

<tr>
<td class="org-right">5</td>
</tr>
</tbody>
</table>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />
</colgroup>
<tbody>
<tr>
<td class="org-right">Bebe refrigerante ou cerveja</td>
</tr>

<tr>
<td class="org-right">10</td>
</tr>
</tbody>
</table>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />
</colgroup>
<tbody>
<tr>
<td class="org-right">Somente refrigerante</td>
</tr>

<tr>
<td class="org-right">5</td>
</tr>
</tbody>
</table>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />
</colgroup>
<tbody>
<tr>
<td class="org-right">Somente cerveja</td>
</tr>

<tr>
<td class="org-right">15</td>
</tr>
</tbody>
</table>

<p>
Menor de 18 anos não pode comprar o ingresso.
</p>
</div>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="date">Created: 2019-08-13 ter 18:53</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>

