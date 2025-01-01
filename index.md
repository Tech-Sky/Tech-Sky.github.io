---
layout: default
title: Home
---

# Welcome to Tech Sky Blog

Explore my latest posts below:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span> - {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
