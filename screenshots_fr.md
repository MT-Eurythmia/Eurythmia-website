---
layout: default_fr
title: Captures d'écran
tab: Screenshots
---

{% assign sh = site.collections | where: "label", "screenshots" | first %}

{% for screenshot in sh.files %}

![Screenshot](screenshots/{{ screenshot.name }})

{% endfor %}
