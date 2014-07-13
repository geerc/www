---
title: Using Major to Perform Mutation Analysis of Java Programs
layout: blog
categories: [research, testing, mutation, Java]
authors: Gregory M. Kapfhammer
mapped: true 
header: false 
research: false 
paper: false
backup: ../../../../../../../../
---

## {{ page.title }}
### <em>{{ page.date | date_to_long_string }}</em>

There is a wonderful way to perform mutation testing of Java programs.

{% highlight bash %}
$ javac -XMutator:ALL MyFile.java
# Generated Mutants: 190 (96 ms)
{% endhighlight %}

