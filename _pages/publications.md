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
<h2>Work in Progress</h2>
<ul>
   <li>Measuring Dependence between Events, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a></li>
   <li>Correlation Coefficients for Discrete Random Variables, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a></li>
   <li>Modeling Illegal Drug Participation of Adolescents Through Distribution Regression, with <a href="https://sites.google.com/view/daniel-gutknecht/home">Daniel Gutknecht</a> and Cenchen Liu</li>
   <li>Generalised Residual Diagnostics, with <a href="https://sites.google.com/view/marcpohle/home">Marc-Oliver Pohle</a>, <a href="https://econstat.statistik.tu-dortmund.de/lehrstuhl/arbeitsgruppe/demetrescu/e">Matei Demetrescu</a> and <a href="https://econstat.statistik.tu-dortmund.de/lehrstuhl/arbeitsgruppe/demetrescu/e">Timo Dimitriadis</a></li>
</ul>


