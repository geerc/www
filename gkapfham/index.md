---
title: Gregory M. Kapfhammer
layout: defaults
categories: [main]
---

# Gregory M. Kapfhammer

Welcome! My name is Gregory M. Kapfhammer and I am an Associate Professor in
and Chair of the [Department of Computer Science](http://www.cs.allegheny.edu)
at [Allegheny College](http://www.allegheny.edu). I
[teach]({{site.baseurl}}/teaching/) courses, conduct
[research]({{site.baseurl}}/research/), create
[software]({{site.baseurl}}/software/), and [serve]({{site.baseurl}}/service/)
organizations in technical areas such as software engineering, software
testing, and data science. In addition to delivering seminars about research
methods and effective communication, I serve as an academic and research
adviser for undergraduate and graduate students. If you would like to learn
more about me, then you can read my [biography]({{site.baseurl}}/biography/).

{% comment %} or {% endcomment %}
{% comment %} view my curriculum vitae as either a <a target="_blank" href = {% endcomment %}
{% comment %} "{{site.baseurl}}cv/curriculum_vitae_kapfhammer.pdf">PDF</a> or an <a {% endcomment %}
{% comment %} target="_blank" href = {% endcomment %}
{% comment %} "{{site.baseurl}}cv/curriculum_vitae_kapfhammer.html">HTML5</a> document. {% endcomment %}

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
