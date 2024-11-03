---
layout: page
permalink: /publications/
title: publications
description: 
years: [2024, 2023, 2022, 2020,2016]
nav: true
nav_order: 1
scholar:
  last_name: [Chen]
  first_name: [Jiangce]
---

See also my <a href="https://scholar.google.com/citations?hl=en&user=UEjqOxIAAAAJ">Google scholar</a> 

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
