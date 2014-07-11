---
id: 0
title: Teaching Distributed Systems to Undergraduates&#58;  An Experience Report 
layout: defaults
categories: [research, presentation, conference, education, systems]
authors: Gregory M. Kapfhammer 
mapped: true 
header: false 
research: false 
paper: false
presentation: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{backup}}/download/research/presentations/jcm2002-kapfhammer-presentation.pdf "Download this Paper!")

### {{page.authors }}

### <em>Presented at the Sixth Jini Community Meeting</em>, June 2002

### Abstract

In the book Zen and the Art of Motorcycle Maintenance, Robert M. Pirsig writes the following: "When I think of the
formal scientific method an image sometimes comes to mind of an enormous juggernaut, a huge bulldozer– slow, tedious,
lumbering, laborious, but invincible. It takes twice as long, five times as long, maybe a dozen times as long as
informal mechanic's techniques, but you know in the end you're going to get it." In this presentation, we will highlight
an undergraduate course taught at a small liberal arts college that attempted to ensure that students "got" the
fundamental theories and practices associated with distributed systems. We will report on the state of current texts and
examine the accessibility of topics that are traditionally associated with the study of distributed systems. Finally, we
will peek into the experiences of students as they applied the "enormous juggernaut" known as the scientific method
during their initial forays into the development of distributed systems with the Jini network technology.  There has
been much attention to testing applications that interact with database management systems, and the testing of
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



