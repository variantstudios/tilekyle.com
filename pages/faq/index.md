---
layout: page
title: FAQ
subtitle: Do you have questions? Below you will find a few commonly asked questions and answers.
permalink: /faq/
header_image_path: /assets/images/work/wendys/003.jpg
---


{% assign faqs = site.data.faq %}{% for faq in faqs	sort: 'weight' %}<div class="faq-item"> <h4 class="faq-question" >Q: {{ faq.question }}</h4> <div class="faq-answer">A: {{ faq.answer }}</div></div>{% endfor %}