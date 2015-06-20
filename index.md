---
layout: page
title: AI Works!
tagline: Random Musings
---
{% include JB/setup %}

## Machine Leaning Posts
## Programming Posts

## Update Author Attributes


## Recent Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
