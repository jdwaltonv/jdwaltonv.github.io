---
layout: default
title: Projects
permalink: /projects/
---

{% include nav.html %}

### Projects
- Netgear LED Toggle Automation
- Networking
- Grafana SIEM

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url | relative_url }}): {{ project.description }}
{% endfor %}
