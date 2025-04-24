---
layout: home
title: 欢迎来到我的博客
---

# 欢迎来到我的博客

这里是我记录技术学习和生活点滴的地方。

## 最新文章

{% for post in site.posts %}
  <h2>
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </h2>
  <p>{{ post.excerpt }}</p>
{% endfor %} 