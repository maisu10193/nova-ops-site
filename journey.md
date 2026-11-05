---
layout: default
title: Journey
permalink: /journey/
---

# Journey

Write a short line about what readers will find here.

{% for post in site.posts %}
<a class="card" href="{{ post.url }}"><div class="meta">{{ post.date | date: "%-d %b %Y" }}{% if post.topic %} · {{ post.topic }}{% endif %}</div><h3>{{ post.title }}</h3><p>{{ post.description }}</p></a>
{% endfor %}
