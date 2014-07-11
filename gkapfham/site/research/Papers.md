---
title: Papers 
layout: defaults
categories: [research]
mapped: true 
header: false 
research: true
backup: ../../../
---

# {{ page.title }}
<ul class="fa-ul">
{% assign max_id = -45 %}
{% for cid in (max_id..1) %}
    {% for page in site.pages %}
        {% if page.id == cid %}
            {% if page.paper == true %}
                {% assign lastcategory = page.categories | last %}
                <li><i class="fa-li fa fa-file-text-o fa-lg"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize }}</a></li>
                <em>Authors</em>: {{ page.authors }} <br>
                <em>Categories</em>: 
                {% for category in page.categories %}
                    {{ category }}{% if category != lastcategory %},
                    {% endif %} <!-- End the category if statement --> 
                {% endfor %} 
            {% endif %}
        {% endif %}
        <p>
    {% endfor %} 
{% endfor %} 
</ul>

