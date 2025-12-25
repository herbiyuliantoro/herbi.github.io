---
layout: single
title: "Writing"
permalink: /writing/
---

Notes, paper summaries, and thoughts.

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url | relative_url }})**  
  <small>{{ post.date | date: "%Y-%m-%d" }}{% if post.tags %} · {{ post.tags | join: ", " }}{% endif %}</small>
{% endfor %}
