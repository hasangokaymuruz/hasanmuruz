---
layout: default
title: Ana Sayfa
---

# Hoş Geldiniz! 👋

Merhaba, ben Hasan. Bu blogda deneyimlerimi, öğrendiklerimi ve düşüncelerimi paylaşıyorum.

## 📝 Son Blog Yazıları

{% for post in site.posts limit:5 %}
  <div style="margin-bottom: 20px; padding: 15px; border-left: 3px solid #00ff41;">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p style="color: #8b949e;">{{ post.date | date: "%d %B %Y" }}</p>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}

---

## 🚀 Hakkımda

Teknoloji, yazılım ve kişisel gelişim üzerine yazılar paylaşıyorum.

## 📬 İletişim

GitHub: [@hasangokaymuruz](https://github.com/hasangokaymuruz)
