---
layout: default
permalink: /authors/index.html
---

## Autoren

Auf dieser Seite möchten wir Ihnen unsere in diesem Blog aktiven Mitarbeiter und Autoren vorstellen:

<ul>
{% assign authors = site.authors | sort: 'name' %}
{% for author in authors %}
	<li><a href="{{ site.baseurl }}{{author.url}}">{{author.name}}</a></li>
{% endfor %}
</ul>
