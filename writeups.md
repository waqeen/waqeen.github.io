---
layout: default
title: WriteUps
permalink: /writeups/
---
# Writeups
Список всех прохождений:

<ul>
  {% for writeup in site.writeups %}
    <li>
      <a href="{{ writeup.url | relative_url }}">{{ writeup.title }}</a>
    </li>
  {% endfor %}
</ul>