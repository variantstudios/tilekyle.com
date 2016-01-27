---
layout: page
title: "Work"
subtitle: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur."
permalink: /work/
header_image_path: "../assets/images/work/wendys/003.jpg"
---

<div class="product-items">
  {% for work in site.work %}
  	<div class="product-item">
  	  	<a href="{{ work.permalink }}">
  	  		<div class="product-image">
            <img src="{{ work.images.first.image_path }}" alt="{{ work.title }}">
          </div>
  		    <h2 class="product-title">{{ work.title }}</h2>
  		    <h5 class="product-location">{{ work.location }}</h5>
  	  	</a>
  	</div>
  {% endfor %}
</div>