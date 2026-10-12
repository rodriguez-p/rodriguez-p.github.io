---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
  
---

<!-- Tip: to show this section later, remove the Liquid comments -->
{% comment %}
<!-- Preprints/Submitted Works -->
{% bibliography -f preprints --group_by none --group_order none %}

<div class="publications">
  <h2 class="bibliography-title">preprints/submitted works</h2>
  <h2 class="bibliography"></h2>
</div>
{% endcomment %}

<!-- Peer-reviewed papers -->
<div class="publications">
  <h2 class="bibliography-title">peer-reviewed publications</h2>
  {% bibliography -f papers %}
</div>

