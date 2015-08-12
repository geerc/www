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

<a title="Lines & Beads" href="http://flickr.com/photos/mrpikachu1/10133867075"><img class="img-responsive-tight" src="http://farm4.static.flickr.com/3764/10133867075_2eef7bbc80_z.jpg" /></a><br /><small><a title="Lines & Beads" href="http://flickr.com/photos/mrpikachu1/10133867075">flickr photo</a> shared by <a href="http://flickr.com/people/mrpikachu1">Mr. Pikachu</a> under a <a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">Creative Commons ( BY-NC-ND ) license</a> </small>

<ul class="fa-ul">
{% directory path: download/research/presentations reverse: 'true' %}
<li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ file.url | remove_first:'/'}}" >{{ file.slug | replace: '-', ' ' | capitalize_all }}</a></li> Presented {{ file.date | date: '%B %Y' }} <p>
{% enddirectory %}
</ul>

