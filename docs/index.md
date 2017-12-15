---
title: Bad Ad Examples
noindex: true
---

Here is a list of pages that contain various types of Javascript redirects:

<dl>
{% for page in site.html_pages %}
	{% unless page.noindex %}
		<dt><a href="{{ page.url | relative_url }}">{{ page.title }}</a></dt>
		<dd>
			<p><code>{{ page.url | absolute_url }}</code></p>
		</dd>
	{% endunless %}
{% endfor %}
</dl>
