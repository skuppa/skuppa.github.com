---
layout: page
title: Kuppas's blog
tagline: Yet another blog, to echo what I have learned...
---
{% include JB/setup %}


## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

* In progress complete the template and render post excerpt
