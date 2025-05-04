---
layout: page
title: Research
permalink: /researches/
description: Dr. Bi's research primarily focuses on leveraging large-scale model technologies for the study of psychiatric pathology, incorporating functional and structural MRI data, clinical data, and more. Additionally, Dr. Bi employs deep learning techniques to identify biomarkers for psychiatric disorders and various brain diseases.
nav: true
nav_order: 5
# display_categories: []
horizontal: true
---

<!-- pages/research.md -->
<div class="projects">

<!-- Display projects without categories -->

{% assign sorted_projects = site.researches | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

 
<div class="cw-research-projects-wrap">
    {% for project in sorted_projects %}
      {% include researches_horizontal.liquid %}
    {% endfor %}
</div>
 
{% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include researches.liquid %}
    {% endfor %}
  </div>
{% endif %}

</div>
