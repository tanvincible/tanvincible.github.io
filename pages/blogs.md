---
layout: default
title: Blogs
permalink: /blogs/
---

#### [Home](/) | [About](/about/) | [bitzany](https://bitzany.netlify.app/) | [Notes](/notes/) | [GitHub](https://github.com/tanvincible)

# Blogs

*A blog is just a socially acceptable way to talk to yourself—except now the whole internet can eavesdrop.*

{% for post in site.posts %}
- [**{{ post.title }}**]({{ post.url }}) <br>
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}
