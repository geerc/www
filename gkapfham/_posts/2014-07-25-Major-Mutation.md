---
title: Using Major to Perform Mutation Analysis of Java Programs
layout: blog_n
categories: [blog, research, testing, mutation, Java]
authors: Gregory M. Kapfhammer
mapped: true 
header: false 
research: false 
paper: false
backup: ../../../../../../../../
---

## {{ page.title }}
### <em>{{ page.date | date_to_long_string }}</em>

<a title="Speed..." href="http://flickr.com/photos/rhk313/3707813723"><img class="img-responsive-tight" src="http://farm3.static.flickr.com/2577/3707813723_6750e6bc8b_z.jpg" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-sa/2.0/">creative commons licensed ( BY-NC-SA )</a> <a title="Speed..." href="http://flickr.com/photos/rhk313/3707813723">flickr photo</a> shared by <a href="http://flickr.com/people/rhk313">Rami ™</a></small>



{% highlight bash %}
$ javac -XMutator:ALL MyFile.java
# Generated Mutants: 190 (96 ms)
{% endhighlight %}

