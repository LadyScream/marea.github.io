---
title: Proyectos
---

Algunos proyectos personales:

{% for category in site.data.projects %}
## {{category.name}}
<ul style="--p:0;">
  {% for project in category.entries %}
  <li style="--mb: 1em;">
    <a href="{{project.url}}">{{project.name}}</a> — {{project.description}}
    {% if project.img %}
    <img src="{{project.img}}" alt="{{project.name}}" style="--w:600px;--maxw:100%;--m:0 auto;--d:block;">
    {% endif %}
  </li>
  {% endfor %}
</ul>
{% endfor %}
