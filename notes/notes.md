---
layout: default
title: Notes
permalink: /notes/
---

#### [Home](/) | [About](/about/) | [Blogs](/blogs/) | [Notes](/notes/) | [GitHub](https://github.com/tanvincible)

# Notes

Random notes about things that I find interesting.

_Notes will be posted shortly._

{% for note in site.notes %}
  - [{{ note.title }}]({{ note.url }}) ({{ note.date | date: "%B %d, %Y" }})
{% endfor %}
