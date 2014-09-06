---
id: -35
title: Using Non-Redundant Mutation Operators and Test Suite Prioritization to Achieve Efficient and Scalable Mutation Analysis
layout: researchpaper_n
categories: [research, paper, conference, mutation testing, regression testing]
authors: Ren&eacute; Just, Gregory M. Kapfhammer, and Franz Schweiggert
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/issre2012-just-kapfhammer-schweiggert.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 23rd International Symposium on Software Reliability Engineering</em>, November 2012

### Abstract

Mutation analysis is a powerful and unbiased technique to assess the quality of input values and test oracles. However,
its application domain is still limited due to the fact that it is a time consuming and computationally expensive
method, especially when used with large and complex software systems. Addressing these challenges, this paper makes
several contributions to significantly improve the efficiency of mutation analysis. First, it investigates the decrease
in generated mutants by applying a reduced, yet sufficient, set of mutants for replacing conditional (COR) and
relational (ROR) operators. The analysis of ten real-world applications, with 400,000 lines of code and more than
550,000 generated mutants in total, reveals a reduction in the number of mutants created of up to 37% and more than 25%
on average. Yet, since the isolated use of non-redundant mutation operators does not ensure that mutation analysis is
efficient and scalable, this paper also presents and experimentally evaluates an optimized workflow that exploits the
redundancies and runtime differences of test cases to reorder and split the corresponding test suite. Using the same ten
open-source applications, an empirical study convincingly demonstrates that the combination of non- redundant operators
and prioritization leveraging information about the runtime and mutation coverage of tests reduces the total cost of
mutation analysis further by as much as 65%.
