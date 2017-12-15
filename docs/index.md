---
title: Bad Ad Examples
noindex: true
---

<ul>
{% for page in site.html_pages %}
	{% unless page.noindex %}
		<li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
	{% endunless %}
{% endfor %}
</ul>
