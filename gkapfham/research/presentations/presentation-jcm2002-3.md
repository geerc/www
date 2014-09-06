---
id: -2
title: Building Distributed Genetic Algorithms with the Jini Network Technology  
layout: researchpresentation_n
categories: [research, presentation, conference, distributed systems, evolutionary computation]
authors: Brian Zorman, Gregory M. Kapfhammer, and Robert S. Roos
mapped: true 
header: false 
research: false 
paper: false
presentation: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{backup}}/download/research/presentations/jcm2002-kapfhammer-presentation-3.pdf "Download this Presentation!")

### {{page.authors }}

### <em>Presented at the Sixth Jini Community Meeting</em>, June 2002

### Abstract

The island model for distributed genetic algorithms (GAs) is a natural match for the master-worker paradigm in
distributed computation. In this presentation, we will explore the benefits and drawbacks of several distributed system
architectures in developing an implementation of a distributed GA that exploits the Jini and JavaSpace technologies. Our
results, using the knapsack problem as an illustration, show that there is an unavoidable price to pay in terms of
decreasing computation-to-communication ratios as a function of instance size. However, we can diminish these effects by
expanding the number of JavaSpaces beyond those required for the obvious implementation. Our results also indicate that
as the number of remote machines increases the potential for a better solution also rises. Even though our distributed
GAs did not always exploit this potential for a higher quality solution, we believe that the combination of Java, Jini,
and JavaSpaces presents avenues for easily distributing the computation of genetic algorithms.

