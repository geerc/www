---
title: Biography 
layout: defaults
categories: [main]
weight: 1
mapped: false
header: true
backup: ../../../
---

{% for cat in site.category-list %}
### {{ cat | capitalize }}
<ul>
{% for page in site.posts %}
{% if page.mapped == true %}
{% for pc in page.categories %}
{% if pc == cat %}
<li><a href="{{ page.url }}">{{ page.title | capitalize }}</a></li>
{% endif %}   <!-- cat-match-p -->
{% endfor %}  <!-- page-category -->
{% endif %}   <!-- resource-p -->
{% endfor %} <!-- page -->
</ul>
{% endfor %}  <!-- cat -->
