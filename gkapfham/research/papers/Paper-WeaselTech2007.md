---
id: -14
title: Efficient Time-Aware Prioritization with Knapsack Solvers
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Sara Alspaugh, Kristen R. Walcott, Michael Belanich, Gregory M. Kapfhammer, and Mary Lou Soffa
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/weaseltech2007-alspaugh-walcott-belanich-kapfhammer-soffa.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the ACM International Workshop on Empirical Assessment of Software Engineering Languages and Technologies</em>, November 2007 

### Abstract

Regression testing is frequently performed in a time constrained environment. This paper explains how 0/1 knapsack
solvers (e.g., greedy, dynamic programming, and the core algorithm) can identify a test suite reordering that rapidly
covers the test requirements and always terminates within a specified testing time limit. We conducted experiments that
reveal fundamental trade-offs in the (i) time and space costs that are associated with creating a reordered test suite
and (ii) quality of the resulting prioritization. We find knapsack-based prioritizers that ignore the overlap in test
case coverage incur a low time overhead and a moderate to high space overhead while creating prioritizations exhibiting
a minor to modest decrease in effectiveness. We also find that the most sophisticated 0/1 knapsack solvers do not always
identify the most effective prioritization, suggesting that overlap-aware prioritizers with a higher time overhead are
useful in certain testing contexts.
