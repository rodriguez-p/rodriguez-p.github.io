---
layout: page
permalink: /publications/
title: publications
years: [2024,2023]
nav: true
nav_order: 2

---

<div class="publications">

<h2 class="year">Preprints</h2>
{% bibliography -f preprints %}


{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>