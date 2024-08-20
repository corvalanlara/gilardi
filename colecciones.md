---
layout: default
title: "Colecciones"
---
<main>
	<div class="section">
		<div class="container">
			<ul>
			{% for coleccion in site.colecciones %}
			<li><a href="{{ coleccion.url }}">{{ coleccion.title }} ({{ coleccion.year }})</a></li>

			{% endfor %} 
			</ul>
		</div>
	</div>
</main>

