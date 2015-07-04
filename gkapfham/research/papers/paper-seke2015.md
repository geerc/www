---
id: -48
title: Automatically Evaluating the Efficiency of Search-Based Test Data Generation for Relational Database Schemas
layout: researchpaper_n
categories: [research, paper, conference, database, testing]
authors: Cody Kinneer, Gregory M. Kapfhammer, Chris J. Wright, and Phil McMinn
mapped: true
header: false
research: false
paper: true
backup: ../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/seke2015-kinneer-kapfhammer-wright-mcminn.pdf "Download this Paper!")

### {{page.authors}}

### <i>Proceedings of the 27th International Conference on Software Engineering and Knowledge Engineering</i>, June 2015.

### Abstract

The characterization of an algorithm's worst-case time complexity is useful because it succinctly captures how its
runtime will grow as the input size becomes arbitrarily large.  However, for certain algorithms &mdash; such as those
performing search-based test data generation &mdash; a theoretical analysis to determine worst-case time complexity is
difficult to generalize and thus not often reported in the literature.  This paper introduces a framework that
empirically determines an algorithm's worst-case time complexity by doubling the size of the input and observing the
change in runtime.  Since the relational database is a centerpiece of modern software and the database's schema is
frequently untested, we apply the doubling technique to the domain of data generation for relational database schemas, a
field where worst-case time complexities are often unknown.  In addition to demonstrating the feasibility of suggesting
the worst-case runtimes of the chosen algorithms and configurations, the results of our study reveal performance
trade-offs in testing strategies for relational database schemas.

