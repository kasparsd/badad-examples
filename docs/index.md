---
title: Bad Ad Examples
noindex: true
---

This is a list of pages that contain various types of Javascript redirects. There is also [a text file with all the URLs](urls.txt).

<dl>
{% for page in site.html_pages %}
	{% unless page.noindex %}
		<dt><a href="{{ page.url | relative_url }}">{{ page.title }}</a></dt>
		<dd>
			{{ page.description | markdownify }}
		</dd>
	{% endunless %}
{% endfor %}
</dl>
