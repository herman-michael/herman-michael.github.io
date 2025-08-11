---
layout: page_tableau
permalink: /tableau/
title: tableau
description: tableau public
nav: true
nav_order: 6
pretty_table: true
tableau_embed: |
  <div class="tableau-container">
    <div class="tableau-aspect-ratio">
      <tableau-viz
        id="tableauViz"
        src="https://public.tableau.com/views/SunSensorCalibrationAlgorithms/Dashboard"
        toolbar="bottom"
        hide-tabs="true"
        style="width: 100%; height: 100%;">
      </tableau-viz>
    </div>
  </div>
---

<div class="code">
  {% bibliography --query @herman2025a --group_by none %}
</div>