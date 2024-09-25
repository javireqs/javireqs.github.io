---
layout: posts
title: "Blog"
permalink: /blog/
paginate: true
---

Welcome to my blog! Here, I share insights and updates on cybersecurity, technology, and hardware projects.

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
