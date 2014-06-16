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

## raw output

 [stand development](https://www.flickr.com/search/?tags=standdevelopment&sort=date-posted-desc&user_id=48024574%40N00) (Flickr)

