---
layout: page
permalink: /publications/
title: publications
description: publications by year in reverse chronological order
years: [2021, 2020, 2019, 2016, 2015, 2014, 2012, 2011]
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
