---
layout: page
title: About Us
subtitle: "Who we are and what we've done."
permalink: /about-us/
header_image_path: ../assets/images/work/wendys/003.jpg
---


<div class="staff">
{% for staff in site.data.staff %}
	<div class="staff-member">
		<img src="{{ staff.image_path }}" alt="{{ staff.name }}" />
		<div class="staff-title">
			<h2 class="staff-name">{{ staff.name }}</h2>
			<h3 class="staff-position">{{ staff.position }}</h3>
		</div>
		<div class="staff-bio">{{ staff.bio }}</div>
	</div>
{% endfor %}
</div>