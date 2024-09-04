---
layout: page
permalink: /publications/
title: Research
description:
years:
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
<h2>Working Papers</h2>
<ul>
   <li>Measuring Dependence between Events, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a> and <a href="https://sites.google.com/view/timodimitriadis">Timo Dimitriadis</a> (2024), <a href="https://arxiv.org/abs/2403.17580">Paper</a>, <a href="https://github.com/jan-lukas-wermuth/BCor">R Package</a>, <a href="https://github.com/jan-lukas-wermuth/replication_BCor">Replication Material</a></li>
   <li>Modeling Illegal Drug Participation of Adolescents Through Distribution Regression, with <a href="https://sites.google.com/view/daniel-gutknecht/home">Daniel Gutknecht</a> and Cenchen Liu (2024), <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4904286">Paper</a>, <a href="https://github.com/jan-lukas-wermuth/replication_DRmisr">Replication Material</a></li>
</ul>

<h2>Work in Progress</h2>
<ul>
   <li>Proper Correlation Coefficients for Discrete Random Variables, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a></li>
   <li>Modeling Illegal Drug Participation of Adolescents Through Distribution Regression, with <a href="https://sites.google.com/view/daniel-gutknecht/home">Daniel Gutknecht</a> and Cenchen Liu</li>
   <li>Generalised Residual Diagnostics, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a>, <a href="https://econstat.statistik.tu-dortmund.de/lehrstuhl/arbeitsgruppe/demetrescu/">Matei Demetrescu</a> and <a href="https://sites.google.com/view/timodimitriadis">Timo Dimitriadis</a></li>
   <li>Statistical Inference for Rank Correlations, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a> and <a href="https://www.hsu-hh.de/mathstat/">Christian H. Weiß</a></li>
   <li>Proper Correlation Coefficients for Nominal Random Variables</li>
</ul>


