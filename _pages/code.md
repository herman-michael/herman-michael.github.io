---
layout: page
permalink: /code/
title: code
description: code page
nav: true
nav_order: 3
pretty_table: true
---

<table
  id="table"
  data-toggle="table"
  data-url="{{ '/assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-field="date" data-width="120">Date</th>
      <th data-field="project" data-width="500">Project</th>
      <th data-field="package" data-width="120">Package</th>
      <th data-field="github" data-width="120">Github</th>
      <th data-field="doi" data-width="120">DOI</th>
    </tr>
  </thead>
</table>