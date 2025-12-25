---
layout: single
title: "Experience"
permalink: /experience/
---

Selected projects, research work, and things I’ve built.

{% assign items = site.portfolio | sort: "date" | reverse %}
{% for item in items %}
- **[{{ item.title }}]({{ item.url | relative_url }})**
{% endfor %}
