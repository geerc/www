---
id: -11
title: Testing in Resource Constrained Execution Environments
layout: researchpaper_n
categories: [research, paper, conference, testing]
authors: Gregory M. Kapfhammer, Mary Lou Soffa, and Daniel Moss&eacute;
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ase2005-kapfhammer-soffa-mosse.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the International Conference on Automated Software Engineering</em>, November 2005

### Abstract

Resource constrained embedded devices are becoming increasingly popular and affordable. Software for these devices is
often implemented in the Java programming language because the Java compiler and virtual machine provide enhanced
safety, portability, and the potential for run-time optimization. It is important to verify that a software application
executes correctly in the environment in which it will normally execute, even if this environment is an embedded one
that severely constrains memory resources. Testing can be used to isolate defects within and establish a confidence in
the correctness of a Java application that executes in a resource constrained environment. However, executing test
suites with a Java virtual machine that uses dynamic compilation to create native code bodies can create significant
testing time overheads if memory resources are highly constrained. This paper describes an approach that uses adaptive
code unloading to ensure that it is feasible to perform testing in the actual memory constrained execution environment.
Our experiments demonstrate that code unloading can reduce both the test suite execution time by 34% and the code size
of the test suite and application under test by 78% while maintaining the overall size of the Java virtual machine.
