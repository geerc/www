---
id: -16
title: A Comprehensive Framework for Testing Database-Centric Software Applications
layout: researchpaper_n
categories: [research, paper, conference, database, testing]
authors: Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/dissertation2007-kapfhammer.pdf" Download this Paper!")

### {{page.authors }}

### <em>PhD Dissertation, University of Pittsburgh</em>, April 2007

### Abstract

The database is a critical component of many modern software applications. Recent reports indicate that the vast
majority of database use occurs from within an application program. Indeed, database-centric applications have been
implemented to create digital libraries, scientific data repositories, and electronic commerce applications. However, a
database-centric application is very different from a traditional software system because it interacts with a database
that has a complex state and structure. This dissertation formulates a comprehensive framework to address the challenges
that are associated with the efficient and effective testing of database-centric applications. The database-aware
approach to testing includes: (i) a fault model, (ii) several unified representations of a program's database
interactions, (iii) a family of test adequacy criteria, (iv) a test coverage monitoring component, and (v) tools for
reducing and re-ordering a test suite during regression testing.

This dissertation analyzes the worst-case time complexity of every important testing algorithm. This analysis is
complemented by experiments that measure the efficiency and effectiveness of the database-aware testing techniques. Each
tool is evaluated by using it to test six database-centric applications. The experiments show that the database-aware
representations can be constructed with moderate time and space overhead. The adequacy criteria call for test suites to
cover 20% more requirements than traditional criteria and this ensures the accurate assessment of test suite quality. It
is possible to enumerate data flow-based test requirements in less than one minute and coverage tree path requirements
are normally identified in no more than ten seconds. The experimental results also indicate that the coverage monitor
can insert instrumentation probes into all six of the applications in fewer than ten seconds. Although instrumentation
may moderately increase the static space overhead of an application, the coverage monitoring techniques only increase
testing time by 55% on average. A coverage tree often can be stored in less than five seconds even though the coverage
report may consume up to twenty-five megabytes of storage. The regression tester usually reduces or prioritizes a test
suite in under five seconds. The experiments also demonstrate that the modified test suite is frequently more
streamlined than the initial tests.
