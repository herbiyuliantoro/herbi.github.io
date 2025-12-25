---
layout: single
title: "Experience"
permalink: /experience/
---

{% assign items = site.portfolio | sort: "date" | reverse %}
{% for item in items %}
- **[{{ item.title }}]({{ item.url | relative_url }})**
{% endfor %}
