---
layout: page
permalink: /code/
title: code
description: code page
nav: true
nav_order: 3
pretty_table: true
---

<table id="table"></table>

<script>
  $(function() {
    $('#table').bootstrapTable({
      columns: [
        { field: 'date', title: 'Date' },
        { field: 'project', title: 'Project' },
        { field: 'package', title: 'Package' },
        {
          field: 'github',
          title: 'Github',
          formatter: function(value) { return value; }
        },
        { field: 'doi', title: 'DOI' }
      ],
      url: "{{ '/assets/json/table_data.json' | relative_url }}"
    });
  });
</script>