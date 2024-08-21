---
layout: default
title: "Colecciones"
---
<main>
	<div class="section">
		<div class="container">
			<ul>
			{% for coleccion in site.colecciones %}
			<li><a class="has-text-link" href="{{ coleccion.url | prepend: site.baseurl }}">{{ coleccion.title }} ({{ coleccion.year }})</a></li>

			{% endfor %} 
			</ul>
		</div>
	</div>
</main>

