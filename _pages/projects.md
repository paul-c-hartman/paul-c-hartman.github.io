---
layout: page
title: projects
permalink: /projects.html
---
{% for project in site.projects %}
 - [{{ project.title }}]({{ project.url }})
{% endfor %}