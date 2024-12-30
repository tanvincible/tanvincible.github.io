---
layout: default
title: Blogs
permalink: /blogs/
---

#### [Home](/) | [About](/about/) | [Blogs](/blogs/) | [GitHub](https://github.com/tanvincible)

# Blogs

Welcome to my blog! Here you'll find my thoughts, insights, and learnings.

{% for post in site.posts %}
- [**{{ post.title }}**]({{ post.url }}) <br>
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}
