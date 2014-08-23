---
id: -19
title: An Empirical Comparison of Methods for Compressing Test Coverage Reports
layout: researchpaper_n
categories: [research, paper, conference, testing]
authors: Erik Ostrofsky and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/esem2009-ostrofsky-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <em>Compendium of the 3rd International Symposium on Empirical Software Engineering and Measurement</em>, October 2009

### Abstract

Test coverage monitoring techniques are an integral part of modern methodologies for testing computer software. For
instance, tools such as automated fault localizers, test adequacy calculators, and debuggers all use a coverage report
for various purposes. Recently developed monitoring methods track the coverage of the nodes and edges in a program's
control flow graph, definition-use associations involving program variables, or interaction with the state and
structure of a database. However, a coverage report often balloons in size as the monitor includes additional
details about the behavior of the program, test suite, and other software components such as the operating system
and database. The marked increase in coverage report size is particularly problematic when testing occurs in a
resource constrained embedded environment or on a build/test server that collects coverage results for many programs
over a long time period. Large coverage reports may also limit the efficiency and effectiveness of defect isolation
methods that monitor a remote program and thus transmit coverage data across a network.

