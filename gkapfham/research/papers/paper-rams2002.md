---
id: -6 
title: An Approach for Understanding and Testing Third-Party Software Components
layout: researchpaper_n
categories: [research, paper, conference, testing]
authors: Jennifer Haddox, Gregory M. Kapfhammer, and C.C. Michael
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/rams2002-haddox-kapfhammer-michael.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 48th Reliability and Maintainability Symposium</em>, June 2002 

### Abstract

In this paper, we present an approach to mitigating software risk by understanding and testing third party, or
commercial-off-the-shelf (COTS), software components. Our approach, based on the notion of software wrapping, gives
system integrators an improved understanding of how a COTS component behaves within a particular system. Our approach to
wrapping allows the data flowing into and out of the component at the public interface level to be intercepted. Using
our wrapping approach, developers can apply testing techniques such as fault injection, data collection and assertion
checking to components whose source code is unavailable. 

We have created a methodology for using software wrapping in conjunction with data collection, fault injection, and
assertion checking to test the interaction between a component and the rest of the application. The methodology seeks to
identify locations in the program where the system's interaction with COTS components could be problematic. Furthermore,
we have developed a prototype that implements our methodology for Java applications. The goal of this process is to
allow the developers to identify scenarios where the interaction between COTS software and the system could result in
system failure. We believe that the technology we have developed is an important step towards easing the process of
using COTS components in the building and maintenance of software systems.
