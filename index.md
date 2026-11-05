---
layout: default
---

# Your welcome line here

Write a few sentences about who you are and what this site is for.

## Latest from my journey

{% for post in site.posts limit:3 %}
<a class="card" href="{{ post.url }}"><div class="meta">{{ post.date | date: "%-d %b %Y" }}</div><h3>{{ post.title }}</h3><p>{{ post.description }}</p></a>
{% endfor %}
