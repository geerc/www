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
href = "{{site.baseurl}}cv/curriculum_vitae_kapfhammer.pdf">PDF</a> or an <a target="_blank" href =
"{{site.baseurl}}cv/curriculum_vitae_kapfhammer.html">HTML5</a> document.

### Featured Paper

{% bibliography --query @inproceedings[key=McMinn2016b] --group_by none %}

### Recent Presentation

<div class="featured">
<ul class="fa-ul">
{% directory path: download/research/featuredpresentation reverse: 'true' %}
<li><i class="fa-li fa fa-file-image-o fa-lg"></i><a class="major" href="{{site.baseurl}}{{ file.url | remove_first:'/'}}" >{{ file.slug | replace: '-', ' ' | capitalize_all }}</a></li> Presented {{ file.date | date: '%B %Y' }} <p>
{% enddirectory %}
</ul>
</div>

### Novel Software

<ul class="fa-ul">
<li><i class="fa-li fa fa-code fa-lg"></i><a class="major"
href="https://github.com/redecheck/redecheck-tool">ReDeCheck: An Automated Tool for Testing Responsively Designed Web Sites</a> </li>
Released November 2015
</ul>

### Highlighted Course

<ul class="fa-ul">
{% for page in site.pages %}
  {% if page.course == true and page.featured == true %}
    <li><i class="fa-li fa fa-cog fa-lg"></i><a class="major" href="{{site.baseurl}}{{ page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
    <em>{{page.subtitle}}</em>
  {% endif %}
{% endfor %}
</ul>

### Status Updates

<div id="tw-gkapfham">
</div>
