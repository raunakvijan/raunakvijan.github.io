layout: page	
title: "A list of animals"	
permalink: /projects/	
---	
<h3 class="archive__subtitle">{{"Projects" }}</h3>	
{% for project in site.projects %}	
  <p>{{ project.title }}  </p>
  {% endfor %}
