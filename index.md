---
layout: default
title: Marcelo Martins
---

# Curso de Verão 2017

* [Curso de PHP](https://mrezende.github.io/curso-php)

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
