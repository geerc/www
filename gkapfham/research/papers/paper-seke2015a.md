---
id: -47
title: expOse&#58; Inferring Worst-Case Time Complexity by Automatic Empirical Study
layout: researchpaper_n
categories: [research, paper, conference, database, testing, tool]
authors: Cody Kinneer, Gregory M. Kapfhammer, Chris J. Wright, and Phil McMinn
mapped: true
header: false
research: false
paper: true
backup: ../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/seke2015a-kinneer-kapfhammer-wright-mcminn.pdf "Download this Paper!")

### {{page.authors}}

### <i>Proceedings of the 27th International Conference on Software Engineering and Knowledge Engineering</i>, June 2015.

### Abstract

A useful understanding of an algorithm's efficiency, the worst-case time complexity gives an upper bound on how an
increase in the size of the input, denoted n, increases the execution time of the algorithm, or f(n).  This relationship
is often expressed in the "big-Oh" notation, where f(n) is O(g(n)) means that the time increases by no more than on
order of g(n). Since the worst-case complexity of an algorithm is evident when n is large, one approach for determining
the big-Oh complexity of an algorithm is to conduct a doubling experiment with increasingly bigger input sizes. By
measuring the time needed to run the algorithm on inputs of size n and 2n, the algorithm's order of growth can be
determined.  This paper introduces expOse, a tool to derive an "EXPerimental big-Oh" for supporting "Scalability
Evaluation" &mdash; expOse infers an algorithm's big-Oh order of growth by conducting a doubling experiment automatically.





