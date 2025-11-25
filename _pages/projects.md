---
layout: page
title: Projects
permalink: /projects
---


# Projects


{% for p in site.data.projects %}
## [{{ p.name }}]({{ p.url }})


{{ p.description }}


**Tech:** {{ p.tech }}


---
{% endfor %}
