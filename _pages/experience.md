---
layout: page
title: Experience
permalink: /experience
---


# Experience


{% for e in site.data.experience %}
## {{ e.role }} — {{ e.company }}
**Period:** {{ e.period }}


{{ e.description }}


---
{% endfor %}
