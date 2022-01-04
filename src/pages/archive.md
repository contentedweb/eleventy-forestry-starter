---
layout: layouts/archive.njk
title: Archive
menuLocation: top
eleventyNavigation:
  key: Archive
  order: 999
pagination:
  data: collections.posts 
  size: 20
  reverse: true
  alias: posts
permalink: /archive/{% if pagination.pageNumber > 0 %}{{ pagination.pageNumber }}/{% endif %}
---

All posts, listed in reverse chronological order. 

Alternatively, <a href="/archive/all-posts/">view all posts by year</a> or <a href="/archive/tags/">browse posts by tag</a>
