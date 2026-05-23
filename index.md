---
layout: default
title: ""
---

Hola, soy Cristhian. En algunos otros lugares del Internet también casafuego. Escribo sobre publicidad, creatividad y las cosas que me interesan.

---

## Notas

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
  </li>
{% endfor %}
</ul>
