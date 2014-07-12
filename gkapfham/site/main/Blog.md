---
title: Blog 
layout: defaults
categories: [main]
weight: 5
mapped: false
header: true
backup: ../../../
---

# {{ page.title }}
<ul class="fa-ul">
{% for page in site.posts %}
    <li><i class="fa-li fa fa-edit fa-lg"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize_all }}</a></li>
    <em>Categories</em>: 
    {% for category in page.categories %}
        {% assign lastcategory = page.categories | last %}
        {{ category }}{% if category != lastcategory %},
        {% endif %}
    {% endfor %} 
    <p>
    <em>Date</em>: {{ page.date | date_to_long_string }} <p></p>
{% endfor %} 
</ul>

