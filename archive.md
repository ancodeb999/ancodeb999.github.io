---
layout: page
title: 归档
permalink: /archive/
---

<div class="archive-list">
  {% for post in site.posts %}
  <article class="archive-item">
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y.%m.%d" }}</time>
    <div>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt | strip_html | truncate: 110 }}</p>
    </div>
  </article>
  {% endfor %}
</div>
