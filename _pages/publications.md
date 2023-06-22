---
layout: page
permalink: /publications/
title: research
description:
years:
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<h1>Publications</h1>
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
