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

{% comment %} display all of the research papers that are not edited volumes and published a conference or journal papers {% endcomment %}
## Research Papers
{% bibliography --query @article[keywords!=edit] && @inproceedings && @incollection %}

{% comment %} display all of the theses and dissertations, matching by the keyword that filters them out in the CV {% endcomment %}
## Theses
{% bibliography --query @*[keywords=kapfhammer] %}

{% comment %} display all of the volumes that I have edited, matching on the keyword for the articles {% endcomment %}
## Volumes Edited
{% bibliography --query @article[keywords=edit] %}
