---
title: Talks
layout: defaults
categories: [research]
mapped: true
header: true
research: true
weight: 5
backup: ../../../
---

# {{ page.title }}

<a title="'Aurora Star-Trails' - Cullen, Aberdeenshire" href="http://flickr.com/photos/jixxer/8575524171"><img class="img-responsive-tight" src="http://farm9.static.flickr.com/8506/8575524171_bca0f0e487_z.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">creative commons licensed ( BY-NC-ND )</a> <a title="'Aurora Star-Trails' - Cullen, Aberdeenshire" href="http://flickr.com/photos/jixxer/8575524171">flickr photo</a> shared by <a href="http://flickr.com/people/jixxer">Kristofer Williams</a></small>

<ul class="fa-ul">
{% directory path: download/research/presentations %}
<li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ file.url | remove_first:'/'}}" >{{ file.slug | replace: '-', ' ' | capitalize_all }}</a></li> Presented {{ file.date | date_to_long_string }} <p>
{% enddirectory %}
</ul>

<ul class="fa-ul">
{% assign max_id = -45 %}
{% for cid in (max_id..0) %}
    {% for page in site.pages %}
        {% if page.id == cid %}
            {% if page.presentation == true %}
                {% assign lastcategory = page.categories | last %}
                <li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
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
