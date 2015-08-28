---
layout: default
permalink: /authors/index.html
---

<h3>Autoren</h3>

Auf dieser Seite möchten wir Ihnen unsere in diesem Blog aktiven Mitarbeiter und Autoren vorstellen:

<ul>
{% assign authors = site.authors | sort: 'name' %}
{% for author in authors %}
	<li><a href="{{author.url}}">{{author.name}}</a></li>
{% endfor %}
</ul>
