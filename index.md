---
title: Epiphenomena
layout: default
---

Check out my [projects](/projects) or [contact me](/contact).

# Latest Posts

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
  <p>{{ post.excerpt }}</p>
{% endfor %}
