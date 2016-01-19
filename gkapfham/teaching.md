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

<a title="Gear and Chain" href="http://flickr.com/photos/93751689@N04/9557470061"><img class="img-responsive-tight" src="http://farm4.static.flickr.com/3710/9557470061_a13ffd82e5_z.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by/2.0/">creative commons licensed ( BY )</a> <a title="Gear and Chain" href="http://flickr.com/photos/93751689@N04/9557470061">flickr photo</a> shared by <a href="http://flickr.com/people/93751689@N04">menegue</a></small>

<ul class="fa-ul">
{% assign max_id = -21 %}
{% assign stop_id = 0 %}
{% for cid in (max_id..stop_id) %}
    {% for page in site.pages %}
        {% if page.id == cid %}
            {% if page.course == true %}
                <li><i class="fa-li fa fa-cog fa-lg"></i><a class="major" href="{{site.baseurl}}{{ page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
               <em>{{page.subtitle}}</em>
            {% endif %}
        {% endif %}
        <p>
    {% endfor %}
{% endfor %}
</ul>

## Additional Courses

The course materials for the classes that I taught between the Fall 2000 and Spring 2013 semesters are available if you
[Contact Me]({{site.baseurl}}contact/) with your request. However, please note that the most representative and current
material is accessible through the above sites.
