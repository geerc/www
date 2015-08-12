---
title: Papers
layout: defaults
categories: [research]
mapped: true
header: true
research: true
weight: 4
backup: ../../../
---

# {{ page.title }}

<a title="'The Stars Dance Above Us' - Trwyn Du, Anglesey" href="http://flickr.com/photos/adrian_kingsley-hughes/13149711793"><img class="img-responsive-tight" src="http://farm8.static.flickr.com/7385/13149711793_ca1614f9b0_z.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">creative commons licensed ( BY-NC-ND )</a> <a title="'The Stars Dance Above Us' - Trwyn Du, Anglesey" href="http://flickr.com/photos/adrian_kingsley-hughes/13149711793">flickr photo</a> shared by <a href="http://flickr.com/people/adrian_kingsley-hughes">Adrian Kingsley-Hughes</a></small>

<ul class="fa-ul">
{% assign max_id = -48 %}
{% assign stop_id = 0 %}
{% for cid in (max_id..stop_id) %}
    {% for page in site.pages %}
        {% if page.id == cid %}
            {% if page.paper == true %}
                {% assign lastcategory = page.categories | last %}
                <li><i class="fa-li fa fa-file-text-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
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
