---
layout: page
title: "A list of animals"
permalink: /projects/
---

<ul>
  {% for project in site.project %}
    <li>
      <a href="{{ animal.title }}</a>
    </li>
  {% endfor %}
</ul>
