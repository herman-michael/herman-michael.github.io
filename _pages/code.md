---
layout: page
permalink: /code/
title: code
description: research code releases & open source projects
nav: true
nav_order: 4
pretty_table: true
---

<div class="code">
<h2>research code releases</h2>
<style>
#table th, #table td {
  border-left: none !important;
  border-right: none !important;
}
</style>

<table id="table" data-toggle="table" data-url="{{ '/assets/json/table_code.json' | relative_url }}">
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