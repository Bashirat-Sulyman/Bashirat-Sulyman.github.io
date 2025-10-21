---
layout: single
title: "Projects"
permalink: /projects/
author_profile: false
classes: wide
---

<div class="project-grid">
  {% for post in site.posts %}
    <div class="project-card">
      {% if post.image %}
        <a href="{{ post.url | relative_url }}">
          <img src="{{ post.image | relative_url }}" alt="{{ post.title }}">
        </a>
      {% endif %}
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt | strip_html | truncate: 130 }}</p>
    </div>
  {% endfor %}
</div>

