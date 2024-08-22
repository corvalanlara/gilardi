---
layout: default
title: "Home"
---
<main>
	<div class="section">
		<div class="container">
			<p class="has-text-weight-bold">Projects</p>
			<ul>
			{% for coleccion in site.colecciones %}
			<li><a class="project" href="{{ coleccion.url | prepend: site.baseurl }}">{{ coleccion.title }}</a></li>

			{% endfor %}
			</ul>
			<br>
			<p class="has-text-weight-bold">info</p>
		</div>
	</div>
</main>

