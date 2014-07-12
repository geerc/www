---
id: -1
title: Improving the Jini "Out of Box" Experience&#58; Lessons Learned and Solutions Provided  
layout: researchpresentation
categories: [research, presentation, conference, education, systems]
authors: Geoffrey Arnold, Gregory M. Kapfhammer, Charles R. DiVittorio, Brian A. Hykes, Mehrnoush Moussavi-Aghdam, and James E. Tomayko
mapped: true 
header: false 
research: false 
paper: false
presentation: true
backup: ../../../../../../
---

## {{ page.title }} 

### {{page.authors }}

### <em>Presented at the Sixth Jini Community Meeting</em>, June 2002

### Abstract

In The Mythical Man Month, Frederick P. Brooks Jr. followed the lead of Aristotle and divided all of software technology
into the realms of "essence" and "accidents." To the seasoned Jini developer, CLASSPATH environment variables, RMI
codebases, Java security policies, and Jini URLs are common facets associated with the design and implementation of
distributed systems.  However, the Jini novitiate is often confounded and frustrated by the "accidents" that are
normally associated with the implementation of distributed systems in Jini. In this presentation we highlight some of
the current limiting factors of the Jini "out of the box" experience. Moreover, we present a platform independent
utility for starting a complete Jini environment, including the JavaSpaces service. Written entirely in Java, this
utility contains support for benchmarking JavaSpaces service implementations and it can be used as a replacement for the
Tonic tuple-space benchmarking tool. While this simple utility can be used from the command-line to start a Jini
environment, it can be programatically invoked with standard Java programming language constructs from a client class.
We believe that our simple tool can improve the Jini development experience for beginners and experts alike.


