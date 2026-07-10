---
layout: default
title: Projects
permalink: /projects/
---

<section class="page-header">
  <p class="eyebrow">Projects</p>
  <h1>Finance and accounting portfolio.</h1>
  <p class="lede">A portfolio of selected work samples.</p>
</section>

<section class="section project-gallery-section">
  <div class="project-gallery">
    {% assign portfolio_projects = site.projects | sort: 'order' %}
    {% for project in portfolio_projects %}
      <a class="project-card" href="{{ project.url | relative_url }}" aria-label="Open {{ project.title }}">
        <div class="project-card-preview">
          {% if project.preview_image %}
            <img src="{{ project.preview_image | relative_url }}" alt="Preview of {{ project.title }}">
          {% else %}
            <span>Project preview image</span>
          {% endif %}
        </div>
        <div class="project-card-copy">
          <p class="project-number">Project {{ project.order }}</p>
          <h2>{{ project.title }}</h2>
        </div>
      </a>
    {% endfor %}
  </div>
</section>
