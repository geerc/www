---
id: -42
title: History-based Test Case Prioritization with Software Version Awareness 
layout: researchpaper
categories: [research, paper, conference, regression testing]
authors: Chu-Ti Lin, Cheng-Ding Chen, Chang-Shi Tsai, and Gregory M. Kapfhammer
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{backup}}/download/research/papers/iceccs2013-lin-chen-tsai-kapfhammer.pdf "Download this Paper!")

### {{page.authors}}

### <em>Proceedings of the 18th International Conference on Engineering of Complex Computer Systems</em>, July 2013

### Abstract

Test case prioritization techniques schedule the test cases in an order based on some specific criteria so that the
tests with better fault detection capability are executed at an early position in the regression test suite. Many
existing test case prioritization approaches are code-based, in which the testing of each software version is considered
as an independent process. Actually, the test results of the preceding software versions may be useful for scheduling
the test cases of the later software versions. Some researchers have proposed history-based approaches to address this
issue, but they assumed that the immediately preceding test result provides the same reference value for prioritizing
the test cases of the successive software version across the entire lifetime of the software development process. Thus,
this paper describes ongoing research that studies whether the reference value of the immediately preceding test results
is version-aware and proposes a test case prioritization approach based on our observations. The experimental results
indicate that, in comparison to existing approaches, the presented one can schedule test cases more effectively.
