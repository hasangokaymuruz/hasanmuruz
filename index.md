---
layout: default
title: Ana Sayfa
---

# 🚀 Hoş Geldiniz!

Merhaba! Ben **Hasan**. Bu benim modern ve etkileyici blogum.

## 📚 Son Yazılar

<ul class="post-list">
{% for post in site.posts %}
  <li class="post-item">
    <h2 class="post-title">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>
    <p class="post-date">{{ post.date | date: "%d %B %Y" }}</p>
    {% if post.excerpt %}
    <p class="post-excerpt">{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    {% endif %}
  </li>
{% endfor %}
</ul>

## 🎯 Hakkımda

Bu blogda teknoloji, yazılım ve kişisel deneyimlerimi paylaşıyorum.

<a href="{{ '/hakkimda' | relative_url }}" class="btn">Daha Fazla Bilgi →</a>
