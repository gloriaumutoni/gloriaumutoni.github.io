---
layout: default
title: Blog
permalink: /blog/
---

Welcome to my blog! Here I share my thoughts on technology, learning, and life.

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}
