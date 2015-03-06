---
title: Blog 
layout: defaults
categories: [main]
weight: 7
mapped: false
header: true
backup: ../../../
---

# {{ page.title }}

<a title="Newcastle Graffiti & Train Swish (2011)" href="http://flickr.com/photos/andyproctor/6389470529"><img class="img-responsive-tight" src="http://farm7.static.flickr.com/6215/6389470529_f5cf5d6529_z.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">creative commons licensed ( BY-NC-ND )</a> <a title="Newcastle Graffiti & Train Swish (2011)" href="http://flickr.com/photos/andyproctor/6389470529">flickr photo</a> shared by <a href="http://flickr.com/people/andyproctor">apwbATTACK</a></small>

<ul class="fa-ul">
{% for page in site.posts %}
    <li><i class="fa-li fa fa-edit fa-lg"></i><a class="major" href="{{site.baseurl}}{{ page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
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

