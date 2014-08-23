---
id: -21
title: An Experimental Study of Methods for Executing Test Suites in Memory Constrained Environments
layout: researchpaper_n
categories: [research, paper, conference, testing]
authors: Suvarshi Bhadra, Alexander Conrad, Charles Hurkes, Brian Kirklin, and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ast2009-bhadra-conrad-hurkes-kirklin-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 4th Workshop on the Automation of Software Test</em>, May 2009

### Abstract

Software for memory constrained mobile devices is often implemented in the Java programming language because the Java
compiler and virtual machine (JVM) provide enhanced safety, portability, and the potential for run-time optimization.
However, testing time may increase substantially when memory is limited and the JVM employs a compiler to create native
code bodies. This paper furnishes an empirical study that identifies the fundamental trade-offs associated with a method
that uses adaptive native code unloading to perform memory constrained testing. The experimental results demonstrate
that code unloading can reduce testing time by 17% and the code size of the test suite and application under test by 68%
while maintaining the overall size of the JVM. We also find that the goal of reducing the space overhead of an automated
testing technique is often at odds with the objective of decreasing the time required to test. Additional
experiments reveal that using a complete record of test suite behavior, in contrast to a sample-based profile, does
not enable the code unloader to make decisions that markedly reduce testing time. Finally, we identify test suite
and application behaviors that may limit the effectiveness of our method for memory constrained test execution and
we suggest ways to mitigate these challenges.
