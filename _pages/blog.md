---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

<h3 class="archive__subtitle">공부와 개발 기록</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}