---
layout: page
permalink: /publications/
title: Publications
description: selected
years: [2025, 2024, 2022, 2020, 2018]
nav: true
nav_order: 4
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
<br>
Full list of publications <a href="https://scholar.google.com/citations?user=Rq6m2UIAAAA">here.</a>
