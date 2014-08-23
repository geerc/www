---
id: -29
title: Empirically Identifying the Best Genetic Algorithm for Covering Array Generation
layout: researchpaper_n
categories: [research, paper, conference, genetic algorithm, software testing]
authors: Liang Yalan, Changhai Nie, Jonathan M. Kauffman, Gregory M. Kapfhammer, and Hareton Leung
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ssbse2011-yalan-nie-kauffman-kapfhammer-leung.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 3rd International Symposium on Search Based Software Engineering</em>, September 2011

### Abstract

With their many interacting parameters, modern software systems are highly configurable. Combinatorial testing is a
widely used and practical technique that can detect the failures triggered by the parameters and their interactions. One
of the key challenges in combinatorial testing is covering array generation, an often expensive process that is not
always amenable to automation with greedy methods. Researchers have proposed many techniques to generate covering
arrays. As one of the evolutionary search methods, the genetic algorithm often has been effectively applied to solve
many complex optimization problems in this and other fields. However, the performance of a genetic algorithm is not
always stable and thus significantly impacted by its configurable parameters. Previous studies have not considered
either the exploration of the genetic algorithm's optimal configuration or ways to improve its performance for covering
array generation. In order to close this knowledge gap, we designed three classes of experiments (i.e., a pair-wise,
base choice, and hill climbing experiment) to systemically examine the impacts of and interactions between the genetic
algorithm's five configurable parameters (i.e., population size, number of generations, crossover probability, mutation
probability, and genetic algorithm variant). Overall, the goal of this paper is to answer the following two questions:
(1) Is there an improved configuration of a genetic algorithm for a particular pair-wise SUT? and (2) Is there a common
improved configuration for all pair-wise SUTs?
