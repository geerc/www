---
id: -32
title: Ask and You Shall Receive&#58; Empirically Evaluating Declarative Approaches to Finding Data in Unstructured Heaps
layout: researchpaper_n
categories: [research, paper, conference, performance, programming languages]
authors: William F. Jones and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/sede2011-jones-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 20th International Conference on Software Engineering and Data Engineering</em>, June 2011

### Abstract

This paper reports on experience with the engineering and empirical evaluation of data management software that stores
objects in collections like the ArrayList or Vector. While many programs may retrieve an object from a collection by
iteratively evaluating each object according to a set of condition(s), this imperative retrieval process becomes more
challenging and error-prone as it applies many complex criteria to find the matching objects in multiple collections.
Query languages for unstructured Java virtual machine (JVM) heaps present an alternative to the imperative approach for
finding the matching objects. Using a benchmarking framework that measures the performance of declarative approaches to
identifying certain objects in the JVM heap, this paper empirically evaluates two query languages, JQL and JoSQL. Both
the experiences and the experimental results reveal trade-offs in the performance and overall viability of the query
languages and the imperative approaches.
