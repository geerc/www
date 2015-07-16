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
{% directory path: download/research/presentations reverse: 'true' %}
<li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ file.url | remove_first:'/'}}" >{{ file.slug | replace: '-', ' ' | capitalize_all }}</a></li> Presented {{ file.date | date: '%B %Y' }} <p>
{% enddirectory %}
</ul>

