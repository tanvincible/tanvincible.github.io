---
layout: default
title: Notes
permalink: /notes/
---

#### [Home](/) | [About](/about/) | [bitzany](https://bitzany.netlify.app/) | [Notes](/notes/) | [GitHub](https://github.com/tanvincible)

# Notes

Random notes about things that I find interesting.

_Notes will be posted shortly._

{% assign categories = site.notes | group_by: "category" %}

{% for category in categories %}
## {{ category.name }}

{% for note in category.items %}
- [**{{ note.title }}**]({{ note.url }}) <br>
  <small>{{ note.date | date: "%B %d, %Y" }}</small>
{% endfor %}

{% endfor %}
