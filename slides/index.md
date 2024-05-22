---
layout: default
title: Slides
---
# Slides

{% for post in site.slides %}
<a href='{{ post.url }}'>{{ post.title }}</a>
{% endfor %}
