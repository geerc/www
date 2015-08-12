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

<a title="Sunshiny Day #1" href="http://flickr.com/photos/sirwiseowl/2167695056"><img class="img-responsive-tight" src="http://farm3.static.flickr.com/2332/2167695056_26ed4fcab6_z.jpg" /></a><br /><small><a title="Sunshiny Day #1" href="http://flickr.com/photos/sirwiseowl/2167695056">flickr photo</a> shared by <a href="http://flickr.com/people/sirwiseowl">sirwiseowl</a> under a <a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">Creative Commons ( BY-NC-ND ) license</a> </small>

<ul class="fa-ul">
{% directory path: download/research/presentations reverse: 'true' %}
<li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ file.url | remove_first:'/'}}" >{{ file.slug | replace: '-', ' ' | capitalize_all }}</a></li> Presented {{ file.date | date: '%B %Y' }} <p>
{% enddirectory %}
</ul>

