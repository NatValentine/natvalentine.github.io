---
layout: default
title: Nat Valentine's Blog
---

## Welcome to another page, there should be a blog here somewhere

_yay_

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[back](./)
