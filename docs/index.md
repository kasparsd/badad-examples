---
title: Bad Ad Examples
index: true
---

<ul>
{% for page in site.pages %}
	{% unless page.index %}
		<li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
	{% endunless %}
{% endfor %}
</ul>
