---
id: -22
title: An Empirical Study of Incorporating Cost into Test Suite Reduction and Prioritization
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Adam M. Smith and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/sac2009-smith-kapfhammer.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 24th Symposium on Applied Computing</em>, March 2009

### Abstract

Software developers use testing to gain and maintain confidence in the correctness of a software system. Automated
reduction and prioritization techniques attempt to decrease the time required to detect faults during test suite
execution. This paper uses the Harrold Gupta Soffa, delayed greedy, traditional greedy, and 2-optimal greedy algorithms
for both test suite reduction and prioritization. Even though reducing and reordering a test suite is primarily done to
ensure that testing is cost-effective, these algorithms are normally configured to make greedy choices with coverage
information alone. This paper extends these algorithms to greedily reduce and prioritize the tests by using both
test cost (e.g., execution time) and the ratio of code coverage to test cost. An empirical study with eight real
world case study applications shows that the ratio greedy choice metric aids a test suite reduction method in
identifying a smaller and faster test suite. The results also suggest that incorporating test cost during
prioritization allows for an average increase of 17% and a maximum improvement of 141% for a time sensitive
evaluation metric called coverage effectiveness.

