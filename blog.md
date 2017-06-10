---
layout: default
tab: Blog
title: Blog
---

# Blog

{% for post in site.posts %}
{% if post.layout == "post" %}
* {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}
