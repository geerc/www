---
id: -15
title: Test Suite Reduction and Prioritization with Call Trees
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Adam Smith, Joshua Geiger, Gregory M. Kapfhammer, and Mary Lou Soffa
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ase2007-smith-geiger-kapfhammer-soffa.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the IEEE/ACM International Conference on Automated Software Engineering</em>, November 2007 

### Abstract

This paper presents a tool that (i) constructs tree-based models of a program's behavior during testing and (ii) employs
these trees while reordering and reducing a test suite. Using either a dynamic call tree or a calling context tree, the
test reduction component identifies a subset of the original tests that covers the same call tree paths. The
prioritization technique reorders a test suite so that it covers the call tree paths more rapidly than the initial test
ordering. In support of program and test suite understanding, the tool also visualizes the call trees and the coverage
relationships. For a chosen case study application, the experimental results show that call tree construction only
increases testing time by 13%. In comparison to the original test suite, the experiments show that (i) a prioritized
suite achieves coverage much faster and (ii) a reduced test suite contains 45% fewer tests and consumes 82% less time.