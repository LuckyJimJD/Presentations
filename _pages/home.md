---
layout: page-centered
permalink: /
title: Presentations

---

{% for Presentation in site.Presentations %}
<p><a href="{{ Presentation.url }}.html" target="_blank">{{ Presentation.title }}</a></p>
{% endfor %}
