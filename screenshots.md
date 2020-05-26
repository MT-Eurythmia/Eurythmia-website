---
layout: default
title: Eurythmia screenshots
tab: Screenshots
---

{% assign sh = site.collections | where: "label", "screenshots" | first %}

{% for screenshot in sh.files %}

![Screenshot](screenshots/{{ screenshot.name }})

{% endfor %}
