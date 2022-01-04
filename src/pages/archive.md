---
layout: layouts/archive.njk
title: Archive
permalink: /archive/
eleventyNavigation:
  key: Archive
  order: 300
pagination:
  data: collections.posts 
  size: 20
  reverse: true
  alias: posts
---

{% if page.url == pagination.href.first %}
All posts, listed in reverse chronological order. Alternatively here is a <a href="/archive/all-posts/">list of all my posts</a> on one page. 
{% endif %}
