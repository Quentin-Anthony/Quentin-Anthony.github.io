---
layout: page
permalink: /publications/
title: Publications
description:
years: [2022, 2021, 2020, 2019]
nav: true
---

\* denotes equal contribution

An up-to-date list is available on <a href="https://scholar.google.com/citations?hl=en&user=GDm6BIAAAAAJ">Google Scholar</a>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
