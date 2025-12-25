---
layout: single
title: "Media"
permalink: /media/
---

Slides, posters, videos, and images.

{% assign items = site.media | sort: "date" | reverse %}
{% for item in items %}
- **[{{ item.title }}]({{ item.url | relative_url }})**
{% endfor %}
