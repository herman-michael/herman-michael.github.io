---
layout: page
permalink: /datasets/
title: datasets
description: open source datasets
nav: true
nav_order: 5
pretty_table: true
---

<div class="code">
<h2>open source datasets</h2>
<style>
#table th, #table td {
  border-left: none !important;
  border-right: none !important;
}
</style>

<table id="table" data-toggle="table" data-url="{{ '/assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-field="date">Date</th>
      <th data-field="project">Project</th>
      <th data-field="package">Package</th>
      <th data-field="repo">Github</th>
    </tr>
  </thead>
</table>
</div>