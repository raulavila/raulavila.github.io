---
layout: page
title: Archivos
---

Estos son todos los posts publicados en el blog hasta ahora:
	
{% for post in site.posts %}
  * {{ post.date | date: "%d/%m/%Y" }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}