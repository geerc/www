---
title: Research 
layout: defaults
categories: [main]
weight: 3
mapped: false
header: true
backup: ../../../
---

# {{page.title}} 

<ul class="fa-ul">
{% for page in site.posts %}
{% if page.research == true %}
<li><i class="fa-li fa fa-arrow-right"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize }}</a> </li>
{% endif %} 
{% endfor %}
</ul>

