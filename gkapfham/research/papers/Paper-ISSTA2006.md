---
id: -13
title: Time-Aware Test Suite Prioritization
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Kristen R. Walcott, Mary Lou Soffa, Gregory M. Kapfhammer, and Robert S. Roos
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/issta2006-walcott-soffa-kapfhammer-roos.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the ACM SIGSOFT/SIGPLAN International Symposium on Software Testing and Analysis</em>, June 2006

### Abstract

Regression test prioritization is often performed in a time constrained execution environment in which testing only
occurs for a fixed time period. For example, many organizations rely upon nightly building and regression testing of
their applications every time source code changes are committed to a version control repository. This paper presents a
regression test prioritization technique that uses a genetic algorithm to reorder test suites in light of testing time
constraints. Experiment results indicate that our prioritization approach frequently yields higher average percentage of
faults detected (APFD) values, for two case study applications, when basic block level coverage is used instead of
method level coverage. The experiments also reveal fundamental trade-offs in the performance of time-aware
prioritization. This paper shows that our prioritization technique is appropriate for varied regression testing
environments and explains how the baseline approach can be extended to operate in additional time constrained testing
circumstances.

