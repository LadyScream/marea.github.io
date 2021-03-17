---
title: 
---

# ¡Hola! Soy <span style="--td:underline;">Manuel Arevalo</span>

<figure><img src="/assets/images/me.jpg" alt="Este soy yo :)"
style="--radius:100%;"></figure>

Soy un desarrollador web, escritor y creativo. Actualmente estoy trabajando en
**Hoja Rota**.

## Mira lo más reciente del blog


{% for post in site.posts limit:10 %}
  * [{{post.date | date: "%Y-%m-%d"}} — {{post.title}}]({{post.url}})
{% endfor %}

## Puedes seguirme en:

* [Github 🐙](https://github.com/marea)
* [Twtxt 🐦](https://manuelarevalo.com/twtxt.txt)

## Contáctame:

* [Email ✉️](mailto:m.arevalo.aragon@gmail.com)
