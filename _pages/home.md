---
layout: page-centered
permalink: /
title: Presentations

---

{% for Presentation in site.data.presentations %}
<p><a href="https://www.emfink.net/Presentations/{{ presentation.url }}.html" >{{ presentation.title }}</a></p>
{% endfor %}
