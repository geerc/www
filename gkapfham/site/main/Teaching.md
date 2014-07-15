---
title: Teaching 
layout: defaults
page.date: 2014-06-24:00
categories: [main]
weight: 2
mapped: false
header: true
backup: ../../../
---

# {{ page.title }}

<ul class="fa-ul">
{% for page in site.pages %}
{% if page.course == true %}
<li><i class="fa-li fa fa-arrow-right"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize_all }}</a> </li>
{% endif %} 
{% endfor %}
</ul>

<ul class="fa-ul">
{% assign max_id = -45 %}
{% assign stop_id = 0 %}
{% for cid in (max_id..stop_id) %}
    {% for page in site.pages %}
        {% if page.id == cid %}
            {% if page.course == true %}
                <li><i class="fa-li fa fa-file-text-o fa-lg"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize_all }}</a></li>
               <em>{{page.subtitle}}</em>
            {% endif %}
        {% endif %}
        <p>
    {% endfor %} 
{% endfor %} 
</ul>

