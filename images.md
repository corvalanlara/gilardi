---
layout: default
title: "Images"
---
<main>
	<div class="section">
		<div class="container">
			<div class="section obras">
			{% assign obras = site.obras | reverse  %}
			{% for obra in obras %}
			{% if obra.type == 'image' %}

			{% include columnas.html %}

			{% endif %}
			{% endfor %} <!-- for obra in obras -->
			</div>
		</div>
	</div>
</main>

