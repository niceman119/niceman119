---
layout: default
title: Projects
permalink: /projects
---


# Projects


{% for p in site.data.projects %}
## {{ p.title }}
**Stack:** {{ p.stack }}
[Code/Link]({{ p.link }})


{{ p.summary }}


**Impact / Metrics**
- {% for m in p.metrics %}{{ m }}
- {% endfor %}


---
{% endfor %}