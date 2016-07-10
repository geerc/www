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

## Featured Paper

{% comment %} Display the paper that would display first on the research papers page (must use a different template) {% endcomment %}
{% bibliography --template bibliography_entry_forward --group_by none --max 1 %}

## Recent Presentation

{% comment %} Display the presentation that would display first on the talks page (must use a different template) {% endcomment %}
{% bibliography --query @misc[keywords!=supervised] --group_by none --max 1 %}

## Novel Software

<ul class="fa-ul"> <li><i class="fa-li fa fa-code fa-lg"></i><a class="major" href="https://github.com/AVMf/avmf">AVMf:
Extensible implementation of the alternating variable method in Java</a> </li> Released July 2016 </ul>

## Highlighted Course

<ul class="fa-ul">
{% for page in site.pages %}
  {% if page.course == true and page.featured == true %}
    <li><i class="fa-li fa fa-cog fa-lg"></i><a class="major" href="{{site.baseurl}}{{ page.url | remove_first:'/'}}">{{ page.title | capitalize_all }}</a></li>
    <em>{{page.subtitle}}</em>
  {% endif %}
{% endfor %}
</ul>

## Status Updates

<div id="tw-gkapfham">
</div>
