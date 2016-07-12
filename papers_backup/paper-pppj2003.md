---
id: -8 
title: An Examination of the Run-time Performance of GUI Creation Frameworks 
layout: researchpaper_n
categories: [research, paper, conference, performance, graphics]
authors: Christopher Howell, Gregory M. Kapfhammer, and Robert S. Roos 
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/pppj2003-howell-kapfhammer-roos.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the Second International Conference on the Principles and Practice of Programming in Java</em>, June 2003

### Abstract

The graphical user interface (GUI) is an important component of many software systems. Past surveys indicate that the
development of a GUI is a significant undertaking and that the GUI's source code often comprises a substantial portion
of the program's overall source base. Graphical user interface creation frameworks for popular object-oriented
programming languages enable the rapid construction of simple and complex GUIs. In this paper, we examine the run-time
performance of two GUI creation frameworks, Swing and Thinlet, that are tailored for the Java programming language.
Using a simple model of a Java GUI, we formally define the difficulty of a GUI manipulation event. After implementing a
case study application, we conducted experiments to measure the event handling latency for GUI manipulation events of
varying difficulties. During our investigation of the run-time performance of the Swing and Thinlet GUI creation
frameworks, we also measured the CPU and memory consumption of our candidate application during the selected GUI
manipulation events. Our experimental results indicate that Thinlet often outperformed Swing in terms of both event
handling latency and memory consumption. However, Swing appears to be better suited, in terms of event handling latency
and CPU consumption, for the construction of GUIs that require manipulations of high difficulty levels.

