---
layout: page-centered
permalink: /
title: Presentations

---

{% for Presentation in site.data.presentations %}
<p><a href="{{ "{{ presentation.url }}.html" | prepend: site.baseurl }}">{{ presentation.title }}</a></p>
{% endfor %}
