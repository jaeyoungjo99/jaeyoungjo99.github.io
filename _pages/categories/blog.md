---
layout: archive
title: "Blog"
permalink: /categories/blog/
author_profile: true
---

<h3 class="archive__subtitle">Blog Posts</h3>

{% assign posts = site.categories.blog %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}