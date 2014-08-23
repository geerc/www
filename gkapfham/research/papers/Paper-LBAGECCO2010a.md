---
id: -27
title: A Genetic Algorithm to Improve Linux Kernel Performance on Resource-Constrained Devices
layout: researchpaper_n
categories: [research, paper, conference, genetic algorithm, operating systems]
authors: James Kukunas, Robert D. Cupper, and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/lbagecco2010-kukunas-cupper-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the Late Breaking Abstracts Workshop at the Genetic and Evolutionary Computation Conference</em>, July 2010

### Abstract

As computers become increasingly mobile, users demand more functionality, longer battery-life, and better performance
from mobile devices. In response, chipset fabricators are focusing on elegant architectures to provide solutions that
are both low-power and high-performance. Since these architectures rely on unique x86 extensions rather than fast clock
speeds and large caches, careful thought must be placed into effective optimization strategies for not only user
applications, but also the kernel itself, as the typical default optimizations used by modern compilers do not often
take advantage of these specialized features. Focusing on the Intel Diamondville platform, this paper presents a genetic
algorithm that evolves the compiler flags needed to build a Linux kernel that exhibits reduced response times.
