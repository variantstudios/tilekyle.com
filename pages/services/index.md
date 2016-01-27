---
layout: page
title: "Services"
subtitle: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur."
permalink: /services/
header_image_path: "../assets/images/work/wendys/003.jpg"
---

<div class="services">
{% for service in site.data.services %}
	<h4 class="service-name">{{ service.name }}</h4>
	<div class="service-description">{{ service.description }}</div>
{% endfor %}
</div>