---
layout: default
title: Projects
permalink: /projects/
---

{% include nav.html %}

### Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url | relative_url }}): {{ project.description }}
{% endfor %}
