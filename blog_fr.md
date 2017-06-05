---
layout: default_fr
tab: Blog
title: Blog
---

# Blog

{% for post in site.posts %}
{% if post.layout == "default_fr" %}
* {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}
