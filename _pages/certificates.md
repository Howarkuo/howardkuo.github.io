---
layout: page
title: Certificates
permalink: /certificates
---


# Certificates


{% for c in site.data.certificates %}
### {{ c.name }} — {{ c.issuer }}
**Date:** {{ c.date }}


{% if c.image %}
![cert]({{ c.image }}){:style="width:320px;border:1px solid #ddd;padding:6px;"}
{% endif %}


---
{% endfor %}
