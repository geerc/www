---
id: -25
title: Using Synthetic Test Suites to Empirically Compare Search-Based and Greedy Prioritizers
layout: researchpaper_n
categories: [research, paper, conference, testing]
authors: Zachary Williams and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/lbagecco2010-williams-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the Late Breaking Abstracts Workshop at the Genetic and Evolutionary Computation Conference</em>, July 2010

### Abstract

The increase in the complexity of modern software has led to the commensurate growth in the size and execution time of
the test suites for these programs. In order to address this alarming trend, developers use test suite prioritization to
reorder the test cases so that faults can be detected at an early stage of testing. Yet, the implementation and
evaluation of greedy and search-based test prioritizers requires access to case study applications and their associated
test suites, which are often difficult to find, configure, and use in an empirical study. This paper presents two types
of synthetically generated test suites that support this process of experimentally evaluating prioritization methods.
Using synthetic test suites affords greater control over test case characteristics and supports the identification of
empirical trends that contradict the established wisdom about search-based and greedy prioritization. For instance, we
find that the hill climbing algorithm often exhibits a lower time overhead than the greedy test suite prioritizer while
producing test orderings with comparable effectiveness scores.

