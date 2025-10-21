---
layout: single
title: "Projects"
author_profile: false
classes: wide
---

{% for post in site.posts %}
  <article class="archive__item">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
  </article>
{% endfor %}
