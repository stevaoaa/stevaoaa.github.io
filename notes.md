---
layout: default
title: Notes
---
### Notes

This is a space I intend to use to take notes about stuff that I'm interesting in.

{% for post in site.posts %}
  - **{{ post.date | date_to_string}}**: [{{ post.title }}]({{ post.url }})
{% endfor %}
