---
title: Gregory M. Kapfhammer
layout: defaults
categories: [main]
---

# Gregory M. Kapfhammer

Welcome! My name is Gregory M. Kapfhammer and I am an Associate Professor in and Chair of the [Department of Computer
Science](http://www.cs.allegheny.edu) at [Allegheny College](http://www.allegheny.edu). I teach courses and conduct
research in the areas of algorithms, data structures, software engineering, software testing, data management, mobile
applications, and computer systems.  In addition to organizing and teaching seminars on research methods in computer
science and effective writing and speaking, I serve as an academic and research adviser for undergraduate and graduate
students. If you would like to learn more about me, then you can view my curriculum vitae as either a <a target="_blank"
href = "{{site.baseurl}}cv/curriculum-vitae-kapfhammer.pdf">PDF</a> or an <a target="_blank" href =
"{{site.baseurl}}cv/curriculum-vitae-kapfhammer.html">HTML5</a> document.

### Featured Research Paper

<div class="featured">
<ul class="fa-ul">
{% for page in site.pages %}
  {% if page.paper == true and page.featured == true %}
    <li><i class="fa-li fa fa-file-text-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
    <em>Authors</em>: {{ page.authors }} <br>
  {% endif %}
{% endfor %}
<p>
</ul>
</div>

### Past Research Presentation

<div class="featured">
<ul class="fa-ul">
{% directory path: download/research/recentpresentation reverse: 'true' %}
<li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ file.url | remove_first:'/'}}" >{{ file.slug | replace: '-', ' ' | capitalize_all }}</a></li> Presented {{ file.date | date: '%B %Y' }} <p>
{% enddirectory %}
</ul>
</div>

### Recently Taught Course

<ul class="fa-ul">
{% for page in site.pages %}
  {% if page.course == true and page.featured == true %}
    <li><i class="fa-li fa fa-cog fa-lg"></i><a class="major" href="{{site.baseurl}}{{ page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
    <em>{{page.subtitle}}</em>
  {% endif %}
{% endfor %}
</ul>

### Status Updates from Gregory M. Kapfhammer

<div id="tw-gkapfham">
</div>
