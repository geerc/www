---
title: Research 
layout: defaults
categories: [main]
weight: 3
mapped: false
header: true
backup: ../../../
---

# {{page.title}} 

<a title="footprints in the sky" href="http://flickr.com/photos/40137058@N07/4864666639"><img class="img-responsive-tight" src="http://farm5.static.flickr.com/4098/4864666639_ed8a9fe5b5_b.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-sa/2.0/">creative commons licensed ( BY-NC-SA )</a> <a title="footprints in the sky" href="http://flickr.com/photos/40137058@N07/4864666639">flickr photo</a> shared by <a href="http://flickr.com/people/40137058@N07">lacomj</a></small>

<ul class="fa-ul">
{% for page in site.pages %}
{% if page.research == true %}
<li><i class="fa-li fa fa-arrow-right"></i><a class="major" href="{{ page.url }}">{{ page.title | capitalize }}</a> </li>
{% endif %} 
{% endfor %}
</ul>

