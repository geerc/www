---
id: -30
title: Dynamic Invariant Detection for Relational Databases
layout: researchpaper_n
categories: [research, paper, conference, database, debugging]
authors: Jake Cobb, Gregory M. Kapfhammer, James A. Jones, and Mary Jean Harrold
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/woda2011-cobb-kapfhammer-jones-harrold.pdf" Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 9th International Workshop on Dynamic Analysis</em>, July 2011

### Abstract

Despite the many automated techniques that benefit from dynamic invariant detection, to date, none are able to capture
and detect dynamic invariants at the interface of a program and its databases. This paper presents a dynamic invariant
detection method for relational databases and for programs that use relational databases and an implementation of the
approach that leverages the Daikon dynamic-invariant engine. The method defines a mapping between relational database
elements and Daikon's notion of program points and variable observations, thus enabling row-level and column-level
invariant detection. The paper also presents the results of two empirical evaluations on four fixed data sets and three
subject programs. The first study shows that dynamically detecting and inferring invariants in a relational database is
feasible and 55% of the invariants produced for each subject are meaningful. The second study reveals that all of these
meaningful invariants are schema-enforceable using standards-compliant databases and many can be checked by databases
with only limited schema constructs.

