---
title: Epiphenomena
layout: home
---

I'm looking for [work](resume_2025_08_p.pdf)

# Latest Posts

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
  <p>{{ post.excerpt }}</p>
{% endfor %}
