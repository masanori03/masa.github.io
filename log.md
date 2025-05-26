---
layout: default
title: Tetris Devlog Posts
---

# Development Log

Here is a list of my progress posts documenting the creation of my Tetris game using C++ and Raylib.

<ul>
{% assign sorted_notes = site.notes | sort: 'date' | reverse %}
{% for note in sorted_notes %}
  <li style="margin-bottom: 1.5em;">
    <strong>{{ note.title }}</strong><br>
    🗓️ {{ note.date | date: "%Y-%m-%d" }}<br>
    {{ note.summary }}<br>
    <a href="{{ note.url }}">Read more →</a>
  </li>
{% endfor %}
</ul>
