---
layout: page
title: research
permalink: /research/
description: Research in deep learning and time-series forecasting.
nav: true
nav_order: 1
horizontal: true
---

<!-- Research cards are generated from Markdown files in _projects. -->
<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
<div class="container">
  <div class="row row-cols-1">
  {% for project in sorted_projects %}
    {% include projects_horizontal.liquid %}
  {% endfor %}
  </div>
</div>
</div>
