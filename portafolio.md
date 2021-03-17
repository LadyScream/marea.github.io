---
title: Portafolio
---

Este es un portafolio de proyectos en los que he trabajado:

<ul style="--p:0;">
{% for project in site.data.portfolio %}
  <li style="--mb: 1em;">
    <a href="{{project.url}}">{{project.date | date: "%Y-%m-%d"}} - {{project.name}}</a> — {{project.description}}
    {% if project.img %}
    <img src="{{project.img}}" alt="{{project.name}}" style="--w:600px;--maxw:100%;--m:0 auto;--d:block;">
    {% endif %}
  </li>
{% endfor %}
</ul>
