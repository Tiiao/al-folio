---
layout: page
title: Research
permalink: /research/
description: 
years: [2022, 2021, 2018]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
  <h2 class="pub">Research Interests</h2>
  <span style="line-height:180%">
  <ul>
  <li>High-dimensional statistics and learning</li>
  <li>Deep learning theory</li>
  <li>Data-driven decision making</li>
  </ul>
  </span>

  <h2 class="pub">Preprints <span style="font-size:small">(*: equal contribution)</span></h2>
  {% bibliography -f papers -q @*[preprint=true]* %}

  <h2 class="pub">Publications <span style="font-size:small">(*: equal contribution)</span></h2>
  {% bibliography -f papers -q @*[preprint=false]* %}
</div>
