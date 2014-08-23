---
id: -36
title: An Empirical Comparison of Java Remote Communication Primitives for Intra-Node Data Transmission
layout: researchpaper_n
categories: [research, paper, journal, performance, distributed systems]
authors: Philip F. Burdette, William F. Jones, Brian C. Blose, Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/per2012-burdette-jones-blose-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <em>Performance Evaluation Review</em>, 39(4). April 2012

### Abstract

This paper presents a benchmarking suite that measures the performance of using sockets and eXtensible Markup Language
remote procedure calls (XML-RPC) to exchange intra-node messages between Java virtual machines (JVMs). The paper also
reports on an empirical study comparing sockets and XML-RPC with response time measurements from timers that use both
operating system tools and Java language instrumentation. By leveraging packet filters inside the GNU/Linux kernel, the
benchmark suite also calculates network resource consumption. Moreover, the framework interprets the response time
results in light of memory subsystem metrics characterizing the behavior of the JVM. The empirical findings indicate
that sockets perform better when transmitting small to very large objects, while XML-RPC exhibits lower response time
than sockets with extremely large bulk data transfers. The experiments reveal trade-offs in performance and thus
represent the first step towards determining if Java remote communication primitives can support the efficient exchange
of intra-node messages.
