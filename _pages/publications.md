---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025, 2024, 2023, 2022, 2021]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=Eap1w88AAAAJ&hl=en)] | [[DBLP](https://dblp.org/pid/85/6586.html)]



#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
