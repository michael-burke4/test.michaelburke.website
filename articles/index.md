---
layout: default
title: Articles
---
# Articles

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
