---
title:  "Welcome to Terraform!"
date:   2018-7-16 16:16:01 -0600
categories: terraform
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {{ post.content }}
  {% endfor %}
</ul>
