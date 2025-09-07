---
layout: default
title: Michelle Mobius - Portfolio
permalink: /projects/
---

<div class="gallery-container">
  <div class="project-gallery">
    {% assign sorted_projects = site.projects | sort: 'order' %}
    {% for project in sorted_projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>

