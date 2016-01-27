---
layout: page
title: "FAQ"
subtitle: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur."
permalink: /faq/
header_image_path: "../assets/images/work/wendys/003.jpg"
---

{% assign faqs = site.data.faq %}
{% for faq in faqs | sort: 'weight' %}
<div class="faq-item">
	<h4 class="faq-question" >Q: {{ faq.question }}</h4>
	<div class="faq-answer">A: {{ faq.answer }}</div>
</div>
{% endfor %}