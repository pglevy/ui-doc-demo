---
layout: default
title: Home
---
# {{ site.title }}

{{ site.description }}

<ul>
{% for page in site.pages %}
{% if page.title != "Home" %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</ul>