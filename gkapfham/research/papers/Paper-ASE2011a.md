---
id: -28
title: Localizing SQL Faults in Database Applications
layout: researchpaper_n
categories: [research, paper, conference, database, fault localization]
authors: Sarah R. Clark, Jake Cobb, Gregory M. Kapfhammer, James A. Jones, and Mary Jean Harrold
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ase2011a-clark-cobb-kapfhammer-jones-harrold.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 26th International Conference on Automated Software Engineering</em>, November 2011

### Abstract

This paper presents a new fault-localization technique designed for applications that interact with a relational
database. The technique uses dynamic information specific to the application's database, such as Structured Query
Language (SQL) commands, to provide a fault-location diagnosis. By creating statement-SQL tuples and calculating their
suspiciousness, the presented method lets the developer identify the database commands and the program statements likely
to cause the failures. The technique also calculates suspiciousness for statement-attribute tuples and uses this
information to identify SQL fragments that are statistically likely to be responsible for the suspiciousness of that SQL
command. The paper reports the results of two empirical studies. The first study compares existing and database-aware
fault-localization methods, and reveals the strengths and limitations of prior techniques, while also highlighting the
effectiveness of the new approach. The second study demonstrates the benefits of using database information to improve
understanding and reduce manual debugging effort.

