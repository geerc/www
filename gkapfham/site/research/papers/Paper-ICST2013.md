---
id: -44 
title: Search-Based Testing of Relational Schema Integrity Constraints Across Multiple Database Management Systems
layout: researchpaper
categories: [research, paper, conference, testing, database]
authors: Gregory M. Kapfhammer, Phil McMinn, and Chris J. Wright 
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{backup}}/download/research/papers/icst2013-kapfhammer-mcminn-wright.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 6th International Conference on Software Testing, Verification and Validation</em>, March 2013

### Abstract

There has been much attention to testing applications that interact with database management systems, and the testing of
individual database management systems themselves. However, there has been very little work devoted to testing arguably
the most important artefact involving an application supported by a relational database – the underlying schema. This
paper introduces a search-based technique for generating database table data with the intention of exercising the
integrity constraints placed on table columns. The development of a schema is a process open to flaws like any stage of
application development. Its cornerstone nature to an application means that defects need to be found early in order to
prevent knock-on effects to other parts of a project and the spiralling bug-fixing costs that may be incurred. Examples
of such flaws include incomplete primary keys, incorrect foreign keys, and omissions of NOT NULL declarations. Using
mutation analysis, this paper presents an empirical study evaluating the effectiveness of our proposed technique and
comparing it against a popular tool for generating table data, DBMonster. With competitive or faster data generation
times, our method outperforms DBMonster in terms of both constraint coverage and mutation score.
