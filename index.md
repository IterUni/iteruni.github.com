---
layout: page
title: Home
---
{% include JB/setup %}

# Introduction

Below are lectures. The first lecture about software development is Systems - SYS101.

If you want to understand how Iterative University approaches learning, please start with Learning - LRN101.

## Sample Sessions

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

