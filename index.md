---
layout: default
title: Welcome to DaveOpsIO Blog
---

Welcome to the official blog! Here you'll find posts about DevOps, cloud, automation, and more.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
