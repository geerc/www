---
id: 1
title: An Approach to Identifying and Understanding Problematic COTS Components
layout: defaults
categories: [research, paper, conference, testing]
authors: Gregory M. Kapfhammer, C.C. Michael, Jennifer Haddox, and Ryan Colyer 
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../
---

## {{ page.title }} 

### {{page.authors}}

### <em>Proceedings of the 2nd Software Assurance and Certification Conference</em>, September 2000

### Abstract

The usage of Commercial off the Shelf (COTS) components in software systems presents the possibility of temporal savings
and efficiency increases. However, this temporal savings might come at the expense of system quality. When a system
integrator relies upon COTS software, trust is placed in unknown, black-box components. We present a methodology that
identifies problematic COTS components and then attempts to augment a system integrator's understanding of these
components. Our technique uses software fault injection to expose COTS components to new failure scenarios. When these
unique failure scenarios cause a COTS component to act in an unpredictable manner, our approach records the injected
fault and the anomalous behavior. Next, we employ different machine learning techniques to build a representation of the
anomalous behavior of the COTS component. These machine learning algorithms analyze the collected data, which describes
the diverse conditions that cause a COTS component to behave unpredictably, and produce a comprehensive model of the
combinations of input and component state that normally result in deviant behavior. A system integrator can inspect a
graphical representation of this model in order to gain a better understanding of the anomalous COTS components. We
believe our approach to isolating and understanding problematic COTS components will allow a system integrator to
realize the temporal savings of reusable COTS software while also mitigating the associated risks.



