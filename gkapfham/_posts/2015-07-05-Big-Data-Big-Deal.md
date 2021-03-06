---
title: Is big data a big deal? Not without correct software!
layout: blog_n
categories: [testing, database, ideas]
authors: Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: false
backup: ../../../../../../../
---

# {{ page.title }}
## <em>{{ page.date | date_to_long_string }}</em>

<a title="vases" href="http://flickr.com/photos/mybloodyself/2428544365"><img class="img-responsive-tight" src="http://farm4.static.flickr.com/3094/2428544365_4fdd69c25d_z.jpg" /></a><br /><small><a title="vases" href="http://flickr.com/photos/mybloodyself/2428544365">flickr photo</a> shared by <a href="http://flickr.com/people/mybloodyself">danmachold</a> under a <a href="http://creativecommons.org/licenses/by-nc-sa/2.0/">Creative Commons ( BY-NC-SA ) license</a> </small>

This statement was written to support my participation in a panel at the *27th International Conference on Software
Engineering and Knowledge Engineering*.  To view the accompanying slides for this presentation, please refer to <a
name="Kapfhammer2015a-return"></a> {% cite Kapfhammer2015a %}.  If you want to learn more about new work that my
colleagues and students and I are conducting in the area of efficiently testing data-centric applications, please read
<a name="Kinneer2015-return"></a> {% cite Kinneer2015 %} and <a name="Kinneer2015a-return"></a> {% cite Kinneer2015a %},
two papers that were also presented at the same conference.

Big data analytics software allows researchers and practitioners to create descriptive models and make predictions.
Often characterized by the "three Vs" of volume, velocity, and variety, big data systems must respectively handle large
amounts of data that arrive rapidly and take many different forms. In fields such as evidence-based medicine and the
detection of financial fraud, big data software is poised to and, indeed already is, making important contributions.

However, there is an additional "V" that is often overlooked by both researchers and practitioners: veracity. That is,
if there is a lack of correctness in the software and data that makes up a big data analytics system, then the data
models and the resulting predictions may be compromised &mdash; with serious consequences. For instance, the Data
Warehouse Institute reports that North American organizations experience a $611 billion annual loss due to poor data
quality. Scott W. Ambler argues that the "virtual absence" of software and data testing is the primary cause of this
loss.  Although this example is not specifically tied to big data systems, it clearly illustrates the risks associated
with a lack of veracity in any data-rich field.

The challenge for software testing researchers is to develop and empirically evaluate new methods that can accommodate
the volume, velocity, and variety that is characteristic of big data systems.  While some preliminary work (e.g., the
testing of both data mining systems and database applications) has recently been published, few software engineering
researchers have focused on big data testing. Since veracity is not always considered by big data researchers, the
challenge for these individuals is to create and assess new techniques that, whenever possible, holistically consider
all of the "four Vs". If not already doing so, practitioners in both of these fields should start to establish a
confidence in the correctness of both their software and data through the disciplined use of testing.

The title of my position statement poses the question "is big data a big deal?" Of course, the answer to this question
is "yes". With that said, the increase of big data's importance and impact will be accelerated and even sustained if
researchers and practitioners in fields such as software engineering, software testing, and big data collaborate with
each other to develop efficient and effective data analytics systems that construct high-quality models and make
accurate predictions. Let's collaborate across the fields of software engineering and big data to ensure that we have a
positive influence on society &mdash; thus proving to be a "bigger deal" together than we would have been on our own.

### References

{% bibliography --template bibliography_entry_reference --group_by none --cited %}
