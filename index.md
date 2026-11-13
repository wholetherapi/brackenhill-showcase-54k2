---
layout: default
title: Projects
---

# Projects

{% for page in site.projects %}
- [{{ page.title }}]({{ page.url }})
{% endfor %}
