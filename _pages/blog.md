---
permalink: /blog/
title: "Blog"
layout: single
---

Blank 'Blog' page.

An index of posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

