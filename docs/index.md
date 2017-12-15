---
title: Bad Ad Examples
index: true
---

<ul>
{% for page in site.pages offset:1 %}
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
