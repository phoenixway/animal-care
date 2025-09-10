---
layout: default
title: Home
nav_order: 1
---

# Welcome to the Animal Volunteer Aid

This is a knowledge base for pet owners and zoo volunteers. Use the navigation to find the information you need.

## Recent Articles

<ul>
  {% for post in site.posts limit:10 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>