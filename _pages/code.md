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
  data-url="{{ '/assets/json/table_data.json' | relative_url }}"
  data-escape="false">
  <thead>
    <tr>
      <th data-field="date">Date</th>
      <th data-field="project">Project</th>
      <th data-field="package">Package</th>
      <th data-field="github" data-escape="false">Github</th>
      <th data-field="doi">DOI</th>
    </tr>
  </thead>
</table>

<a class="github-button" href="https://github.com/herman-michael/DSS-CNN" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-show-count="true" aria-label="Star herman-michael/DSS-CNN on GitHub">Star</a>