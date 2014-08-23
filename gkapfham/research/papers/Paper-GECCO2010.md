---
id: -24
title: Empirically Studying the Role of Selection Operators During Search-Based Test Suite Prioritization
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Alexander P. Conrad, Robert S. Roos, and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/gecco2010-conrad-roos-kapfhammer.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the Genetic and Evolutionary Computation Conference</em>, July 2010

### Abstract

Regression test suite prioritization techniques reorder test cases so that, on average, more faults will be revealed
earlier in the test suite's execution than would otherwise be possible. This paper presents a genetic algorithm-based
test prioritization method that employs a wide variety of mutation, crossover, selection, and transformation operators
to reorder a test suite. Leveraging statistical analysis techniques, such as tree model construction through binary
recursive partitioning and kernel density estimation, the paper's empirical results highlight the unique role that the
selection operators play in identifying an effective ordering of a test suite. The study also reveals that, while
truncation selection consistently outperformed the tournament and roulette operators in terms of test suite
effectiveness, increasing selection pressure consistently produces the best results within each class of operator. After
further explicating the relationship between selection intensity, termination condition, fitness landscape, and the
quality of the resulting test suite, this paper demonstrates that the genetic algorithm-based prioritizer is superior to
random search and hill climbing and thus suitable for many regression testing environments.
