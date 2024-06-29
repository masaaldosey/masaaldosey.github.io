---
layout: page
permalink: /books/
title: books
description: 
display_categories: [reading, read]
nav: true
nav_order: 6
horizontal: true
---


<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.books | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
   <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {% endfor %}
  {%- endif -%}
</div>
