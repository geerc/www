---
id: -15
title: Using Coverage Effectiveness to Evaluate Test Suite Prioritizations
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Gregory M. Kapfhammer and Mary Lou Soffa
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the ACM International Workshop on Empirical Assessment of Software Engineering Languages and Technologies</em>, November 2007 

### Abstract

Regression test suite prioritization techniques reorder a test suite with the goal of ensuring that the reorganized test
suite finds faults faster than the initial ordering. It is challenging to empirically evaluate the effectiveness of a
new test case arrangement because existing metrics (i) require fault seeding or (ii) ignore test case costs. This paper
presents a coverage effectiveness (CE) metric that (i) obviates the need to seed faults into the program under test and
(ii) incorporates available data about test case execution times. A test suite is awarded a high CE value when it
quickly covers the test requirements. It is possible to calculate coverage effectiveness regardless of the coverage
criterion that is chosen to evaluate test case quality. The availability of an open source CE calculator enables future
case studies and controlled experiments to use coverage effectiveness when evaluating different approaches to test suite
prioritization.

