---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
  
---

{% comment %}
<!-- Preprints/Submitted Works -->
{% capture preprints %}{% bibliography -f preprints --group_by none --group_order none %}{% endcapture %}
{% if preprints != blank %}
<div class="publications">
  <h2 class="bibliography-title">preprints/submitted works</h2>
  <h2 class="bibliography"></h2>
  {{ preprints }}
</div>
{% endif %}
{% endcomment %}

<!-- Peer-reviewed papers -->
<div class="publications">
  <h2 class="bibliography-title">peer-reviewed publications</h2>
  {% bibliography -f papers %}
</div>
