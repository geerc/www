---
id: -47
title: The effectiveness of test coverage criteria for relational database schema integrity constraints
layout: researchpaper_n
categories: [research, paper, journal, database, testing]
authors: Phil McMinn, Chris J. Wright, and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/per2005-fiedler-walcott-richardson-kapfhammer-amer-chrysanthis.pdf "Download this Paper!")

### {{page.authors }}

### <em>Performance Evaluation Review</em>, 33(4), December 2005

### Abstract

Many applications rely upon a tuple space within distributed system middleware to provide loosely coupled communication
and service coordination. This paper describes an approach for measuring the throughput and response time of a tuple
space when it handles concurrent local space interactions. Furthermore, it discusses a technique that populates a tuple
space with tuples before the execution of a benchmark in order to age the tuple space and provide a worst-case
measurement of space performance. We apply the tuple space benchmarking and aging methods to the measurement of the
performance of a JavaSpace, a current example of a tuple space that integrates with the Jini network technology. The
experiment results indicate that: (i) the JavaSpace exhibits limited scalability as the number of concurrent
interactions from local space clients increases, (ii) the aging technique can operate with acceptable time overhead, and
(iii) the aging technique does ensure that the results from benchmarking capture the worst-case performance of a tuple
space.
