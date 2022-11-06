---
layout: page
permalink: /photography/
title: photography
description: 
display_categories: [munich, prague]
nav: false
nav_order: 6
---


<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {% endfor %}
  {%- endif -%}
</div>