---
title:  "Welcome to Terraform!"
date:   2018-7-16 16:16:01 -0600
categories: terraform
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">1{{ post.title }}3</a>
    </li>
    {{ post.content }}
  {% endfor %}
</ul>
