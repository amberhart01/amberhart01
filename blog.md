---
layout: default
title: Blog
---

# 📝 Blog

Welcome to my security journey log!  
Here are my latest posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
