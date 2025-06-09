---
layout: page
permalink: /publications/
title: publications
years: [2024,2023]
nav: true
nav_order: 2

---


<!-- Preprints/Submitted Works -->
{% capture preprints %}{% bibliography -f preprints %}{% endcapture %}
{% if preprints != blank %}
<div class="publications">
  <h2 class="bibliography-title">Preprints/submitted works</h2>
  {{ preprints }}
</div>
{% endif %}

<div class="publications">
  <h2 class="bibliography-title">Peer-reviewed publications</h2>
  {% bibliography -f papers %}
</div>
