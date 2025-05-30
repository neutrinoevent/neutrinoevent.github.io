---
layout: default
title: Home
---

<h2>Recent Articles</h2>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %-d, %Y" }}</li>
  {% endfor %}
</ul>

