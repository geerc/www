---
id: -46 
title: The Impact of Equivalent, Redundant and Quasi Mutants on Database Schema Mutation Analysis 
layout: researchpaper_n
categories: [research, paper, conference, testing, parameter tuning]
authors: Chris J. Wright, Gregory M. Kapfhammer, and Phil McMinn 
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/qsic2014a-wright-kapfhammer-mcminn.pdf "Download this Paper!")

### {{page.authors }}

### <i>Proceedings of the 14th International Conference on Quality Software</i>, October 2014.

### Abstract

Since the relational database is an important component of real-world software and the schema plays a major role in
ensuring the quality of the database, relational schema testing is essential.  This paper presents methods for improving
both the efficiency and accuracy of mutation analysis, an established method for assessing the quality of test cases for
database schemas.  Using a DBMS-independent abstract representation, the presented techniques automatically identify and
remove mutants that are either equivalent to the original schema, redundant with respect to other mutants, or
undesirable because they are only valid for certain database systems. Applying our techniques for ineffective mutant
removal to a variety of schemas, many of which are from real-world sources like the U.S. Department of Agriculture and
the Stack Overflow website, reveals that the presented static analysis of the DBMS-independent representation is
multiple orders of magnitude faster than a DBMS-specific method. The results also show increased mutation scores in 75\%
of cases, with 44\% of those uncovering a mutation-adequate test suite. Combining the presented techniques yields mean
efficiency improvements of up to 33.7\%, with averages across schemas of 1.6% and 11.8% for HyperSQL and PostgreSQL,
respectively. 

