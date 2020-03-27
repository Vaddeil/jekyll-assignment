---
layout: default
title: Blog
permalink: /blog/
---

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
  <li>
    {{ post.date | date_to_string }}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.excerpt }}
  </li>
  {% endfor %}
</ul>
