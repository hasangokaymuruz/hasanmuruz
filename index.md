---
layout: default
title: Ana Sayfa
---

# Hoş Geldiniz! 👋

Merhaba! Ben Hasan. Bu benim kişisel blogum.

## Son Yazılar

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})  
  *{{ post.date | date: "%d %B %Y" }}*
{% endfor %}
