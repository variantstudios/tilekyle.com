---
layout: page
title: Services
subtitle: 'Tile is our specialty, but we can do all types of floor coverings as well. Below you will find many of the services we provide.'
permalink: /services/
header_image_path: ../assets/images/work/wendys/003.jpg
---


<div class="services">
{% for service in site.data.services %}
	<h4 class="service-name">{{ service.name }}</h4>
	<div class="service-description">{{ service.description }}</div>
{% endfor %}
</div>