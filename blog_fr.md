---
layout: default_fr
tab: Blog
title: Blog
---

{% for post in site.posts %}
{% if post.layout == "post_fr" %}
* {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}
