---
layout: archive
title: "Categories"
permalink: /categories/
author_profile: true
---

{% assign categories = site.categories | sort %}
{% for category in categories %}
  <h3 id="{{ category[0] | slugify }}">{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}