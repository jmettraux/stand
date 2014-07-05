---
layout: site
title: home
---

# stand dev

A blog about stand development.

No expertise, just experiences.

## posts

{% for post in site.posts %}
  <span class="post-link">[{{ post.title }}]({{ post.url }})</span> {{ post.date | date: '%Y-%m-%d' }}
  <div class="excerpt" data-href="{{ post.url }}">
    {{ post.content | strip_html | truncatewords: 49 }}
  </div>
{% endfor %}

## raw output

 [stand development](https://www.flickr.com/search/?tags=standdevelopment&sort=date-posted-desc&user_id=48024574%40N00) (Flickr)

