---
layout: default
title: Post List
---

# Devlog Posts

<ul>
{% for note in site.notes %}
  <li><a href="{{ note.url }}">{{ note.title }}</a></li>
{% endfor %}
</ul>
