---
title: Третья Сторона
permalink: /
layout: page
---

Сайт поддержки проектов

<div class="flex">
{% for post in site.posts %}
<div class="content">
	<h4><a href="{{ post.url }}" title="{{ post.description }}">{{ post.title }}</a></h4>
	<div>{{ post.excerpt }}</div>
	<div class="right"><a href="{{ post.url }}" title="{{ post.description }}">Читать далее...</a></div>
</div>
{% endfor %}
</div>
