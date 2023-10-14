---
layout: page
title: Table of Contents
---

<ul>
  {% for item in site.team1 %}
    {% if item.collection_dir == 'docs' and item.path contains 'team1' %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
