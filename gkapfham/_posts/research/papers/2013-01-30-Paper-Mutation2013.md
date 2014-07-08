---
title: Efficient Mutation Analysis of Relational Database Structure Using Mutant Schemata and Parallelisation 
layout: defaults
categories: [research, paper, conference, testing, mutation, database]
authors: Chris J. Wright, Gregory M. Kapfhammer, and Phil McMinn
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{backup}}/download/research/papers/mutation2013-wright-kapfhammer-mcminn.pdf "Download this Paper!")

### {{page.authors }}

### <i>Proceedings of the The 8th International Workshop on Mutation Analysis</i>, March 2013

### Abstract

Mutation analysis is an effective way to assess the quality of input values and test oracles. Yet, since this technique
requires the generation and execution of many mutants, it often incurs a substantial computational cost. In the context
of program mutation, the use of mutant schemata and parallelisation can reduce the costs of mutation analysis. This
paper is the first to apply these approaches to the mutation analysis of a relational database schema, arguably one of
the most important artefacts in a database application. Using a representative set of case studies that vary in both
their purpose and structure, this paper empirically compares an unoptimised method to four database structure mutation
techniques that intelligently employ both mutant schemata and parallelisation. The results of the experimental study
highlight the performance trade-offs that depend on the type of database management system (DBMS), underscoring the fact
that every DBMS does not support all types of efficient mutation analysis. However, the experiments also identify a
method that yields a one to ten times reduction in the cost of mutation analysis for relational schemas hosted by both
the Postgres and SQLite DBMSs.
