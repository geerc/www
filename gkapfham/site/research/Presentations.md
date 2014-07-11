---
title: Presentations 
layout: defaults
categories: [research]
mapped: true 
header: false 
research: true
backup: ../../../
---

# {{ page.title }}
<ul class="fa-ul">
{% for page in site.posts %}
{% if page.presentation == true %}
{% assign lastcategory = page.categories | last %}
<li><i class="fa-li fa fa-file-text-o fa-lg"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize }}</a> </li>
<em>Authors</em>: {{ page.authors }} <br>
<em>Categories</em>: 
{% for category in page.categories %}
{{ category }}{% if category != lastcategory %},
{{ forloop.index0 }}
{% assign runningcount = forloop.index0 | modulo:3 %}
{{ runningcount }}
{% endif %} 
{% endfor %} <p>
{% endif %}   <!-- cat-match-p -->
{% endfor %} <!-- page -->
</ul>
