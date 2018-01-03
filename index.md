---
layout: default
title: Marcelo Martins
---
# Curso de Verão 2018

* [Curso de Lógica de Programação com Java](https://mrezende.github.io/curso-verao-ime-usp-logica-com-java-2018)

# Curso de Verão 2017

* [Curso de PHP](https://mrezende.github.io/curso-verao-ime-usp-php-2017)

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
