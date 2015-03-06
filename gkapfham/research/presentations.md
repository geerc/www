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

<a title="Brown Tract Pond star trail, New York" href="http://flickr.com/photos/chuckthewriter/14530989582"><img class="img-responsive-tight" src="http://farm6.static.flickr.com/5198/14530989582_25b3a0d2e0_z.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">creative commons licensed ( BY-NC-ND )</a> <a title="Brown Tract Pond star trail, New York" href="http://flickr.com/photos/chuckthewriter/14530989582">flickr photo</a> shared by <a href="http://flickr.com/people/chuckthewriter">chuckthewriter</a></small>

Here is a sampling of my research presentations&mdash;I will add more very soon!

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
