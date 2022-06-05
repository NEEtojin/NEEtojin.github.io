---
layout: page
title: "NEEtojin"
permalink: /blog/
---

# 메모장
개발에 대하여 메모하는 페이지 입니다.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
