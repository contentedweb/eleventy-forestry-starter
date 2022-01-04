---
layout: layouts/archive.njk
title: Archive
eleventyNavigation:
  key: Archive
  order: 999
pagination:
  data: collections.posts 
  size: 2
  reverse: true
  alias: posts
permalink: /archive/{% if pagination.pageNumber > 0 %}{{ pagination.pageNumber }}/{% endif %}
---

All posts, listed in reverse chronological order. 

Alternatively, <a href="/archive/all-posts/">view all posts</a> or <a href="/archive/tags/">browse posts by tag</a>
