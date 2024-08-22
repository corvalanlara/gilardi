---
layout: default
title: "Home"
---
<main>
	<div class="section">
		<div class="container">
			<ul>
			<p class="has-text-weight-bold">projects</p>
			<ul>
			{% for coleccion in site.colecciones %}
			<li><a class="project" href="{{ coleccion.url | prepend: site.baseurl }}">{{ coleccion.title }}</a></li>

			{% endfor %}
			</ul>
			<br>
      			{% for item in site.data.menu %}
      			<li><a class="has-text-weight-bold has-text-black" href="{{ item.url | prepend: site.baseurl }}">
             		{{ item.title }}
      			</a></li>
      			{% endfor %}
			</ul>
		</div>
	</div>
</main>

