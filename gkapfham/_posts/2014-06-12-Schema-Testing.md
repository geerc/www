---
title: Recent Advances in the Testing of Relational Database Schemas
layout: blog_n
categories: [blog, research, testing, database]
authors: Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: false
backup: ../../../../../../../
---

## {{ page.title }}
### <em>{{ page.date | date_to_long_string }}</em>

<a title="Iron Gate, missing Fleur de Lis" href="http://flickr.com/photos/mezzoblue/42717172"><img class="img-responsive-tight" src="https://farm1.staticflickr.com/22/42717172_1d50d09993_z.jpg?zz=1" /></a><br /><small><a href="http://creativecommons.org/licenses/by-nc-nd/2.0/">creative commons licensed ( BY-NC-ND )</a> <a title="Iron Gate, missing Fleur de Lis" href="http://flickr.com/photos/mezzoblue/42717172">flickr photo</a> shared by <a href="http://flickr.com/people/mezzoblue">mezzoblue</a></small>

Database applications are very common and there has been much attention to testing them and the individual database
management systems with which they interact. Yet, there has been very little work devoted to testing arguably the most
important artifact involving an application supported by a relational database&mdash;the underlying schema!

The development of a database schema is a process open to flaws like any stage of application development. Examples of
potential flaws in database schemas include incomplete primary keys, incorrect foreign keys, and omissions of NOT NULL
declarations. The schema's cornerstone nature to a database application means that defects need to be found early in
order to prevent knock-on effects to other parts of an application and the spiralling bug-fixing costs that may be
incurred.

In this important area of testing for relational database schemas, there are many challenges that researchers and
developers need to address. Some recent advances in this field have focused on automatically generating test data to
exercise the constraints with the database schema and assessing the effectiveness of the generated data through the use
of mutation analysis.

The paper "[Search-Based Testing of Relational Schema Integrity Constraints Across Multiple Database Management
Systems]({{site.baseurl}}research/papers/Paper-ICST2013/)" introduces a search-based technique for generating database
table data with the intention of exercising the integrity constraints placed on table columns. The testing tool
described in this paper, [SchemaAnalyst](http://schemaalayst.org/), can automatically generate data that will both
satisfy and negate the constraints in the database schema.

Of course, the process of automatically generating test data raises the question "well, how good is this data?" The
paper "[Efficient Mutation Analysis of Relational Database Structure Using Mutant Schemata and
Parallelisation]({{site.baseurl}}research/papers/Paper-Mutation2013)" introduces efficient techniques for answering this
question.  The presented mutation analysis methods insert simple faults into the schema and check to see whether or not
the test cases can find them.  Intuitively, the tests are not very good if they can not find these faults!

In recent empirical studies designed to evaluate the effectiveness of SchemaAnalyst we compared it to a popular tool for
generating table data, [DBMonster](http://dbmonster.sourceforge.net/). With competitive or faster data generation times,
our method outperforms DBMonster in terms of both the schema constraint coverage and mutation adequacy scores.

