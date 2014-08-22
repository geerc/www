---
id: -12
title: Towards the Prioritization of Regression Test Suites with Data Flow Information
layout: researchpaper_n
categories: [research, paper, conference, regression testing]
authors: Matthew Rummel, Gregory M. Kapfhammer, and Andrew Thall
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ase2005-kapfhammer-soffa-mosse.pdf"Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the ACM SIGAPP Symposim on Applied Computing</em>, March 2005

### Abstract

Regression test prioritization techniques re-order the execution of a test suite in an attempt to ensure that defects
are revealed earlier in the test execution phase. In prior work, test suites were prioritized with respect to their
ability to satisfy control flow-based and mutation-based test adequacy criteria. In this paper, we propose an approach
to regression test prioritization that leverages the all-DUs test adequacy criterion that focuses on the definition and
use of variables within the program under test. Our prioritization scheme is motivated by empirical studies that have
shown that (i) tests fulfilling the all-DUs test adequacy criteria are more likely to reveal defects than those that
meet the control flow-based criteria, (ii) there is an unclear relationship between all-DUs and mutation-based criteria,
and (iii) mutation-based testing is significantly more expensive than testing that relies upon all-DUs.

In support of our prioritization technique, we provide a formal statement of the algorithms and equations that we use to
instrument the program under test, perform test suite coverage monitoring, and calculate test adequacy. Furthermore, we
examine the architecture of a tool that implements our novel prioritization scheme and facilitates experimentation. The
use of this tool in a preliminary experimental evaluation indicates that, for three case study applications, our
prioritization can be performed with acceptable time and space overheads. Finally, these experiments also demonstrate
that the prioritized test suite can have an improved potential to identify defects earlier during the process of test
execution.
