---
layout: page
title: FAQ
subtitle: Do you have questions? Below you will find a few commonly asked questions and answers.
permalink: /faq/
header_image_path: /assets/images/work/wendys/003.jpg
---


{% assign faqs = site.data.faq %}{% for faq in faqs | sort: 'weight' %}&lt;div class="faq-item"&gt;	&lt;h4 class="faq-question" &gt;Q: {{ faq.question }}&lt;/h4&gt;	&lt;div class="faq-answer"&gt;A: {{ faq.answer }}&lt;/div&gt;&lt;/div&gt;{% endfor %}