---
layout: page-centered
permalink: /
title: Presentations

---

{% for Presentation in site.Presentations %}
<p><a href="{{ "{{ Presentation.url }}.html" | prepend: site.baseurl }}">{{ Presentation.title }}</a></p>
{% endfor %}
