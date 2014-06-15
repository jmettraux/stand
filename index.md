---
layout: site
title: home
---

# stand dev

A blog about stand development.

No expertise, just experiences.

## posts

{% for post in site.posts %}
  {{ post.date | date: '%Y-%m-%d' }}  [{{ post.title }}]({{ post.url }})
{% endfor %}

