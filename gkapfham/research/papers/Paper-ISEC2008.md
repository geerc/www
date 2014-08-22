---
id: -18
title: Database-Aware Test Coverage Monitoring
layout: researchpaper_n
categories: [research, paper, conference, database, regression testing]
authors: Gregory M. Kapfhammer and Mary Lou Soffa
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/isec2008-kapfhammer-soffa.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the India Software Engineering Conference</em>, February 2008

### Abstract

Unlike traditional programs, a database-centric application interacts with a database that has a complex state and
structure. Even though the database is an important component of modern software, there are few tools to support the
testing of database-centric applications. This paper presents a test coverage monitoring technique that tracks a
program's definition and use of database entities during test suite execution. The paper also describes instrumentation
probes that construct a coverage tree that records how the program and the tests cover the database. We conducted
experiments to measure the costs that are associated with (i) instrumenting the program and the tests and (ii)
monitoring coverage. For all of the applications, the experiments demonstrate that the instrumentation mechanism incurs
an acceptable time overhead. While the use of statically inserted probes may increase the size of an application, this
approach enables database-aware coverage monitoring that increases testing time from 13% to no more than 54%.
