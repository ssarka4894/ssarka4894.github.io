---
title: "Thesis: Modeling, Analysis and Control of Cart-Inverted Pendulum Systems and Fundamental Tradeoffs"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2009-10-01
venue: 'Journal 1'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This thesis lays down a foundation for more advanced work on bipeds by carefully examining cart
inverted pendulum systems (CIPS, often used to approximate each leg of a biped) and associated closed loop performance
tradeoffs.
A CIPS is characterized by an instability (associated with the tendency of the pendulum to fall) and a right half
plane (RHP, non minimum phase) zero (associated with the cart displacement x). For such a system, the zero is
typically close to (and smaller) than the instability.
As such, a classical PK control structure would result in very poor sensitivity properties.
It is therefore common to use a hierarchical inner outer loop structure.
As such, this thesis examines how such a structure can be used to improve sensitivity properties beyond a classic PK
structure and systematically tradeoff sensitivity properties at the plant input/output.
While the instability requires a minimum bandwidth at the plant input, the RHP zero imposes a maximum bandwidth
on the cart displacement x.
Three CIPSs are examined one with a long pendulum, one with a short pendulum and one with an intermediately
sized pendulum.
We show that while the short pendulum system is the most unstable and requires the largest bandwidth at the plant
input for stabilization (and one might thus say that it is the hardest to control), it also has the largest RHP zero.
Consequently, it will permit the largest cart displacement x bandwidth, and hence, one can argue that the short
pendulum system is easiest to control.
Similarly, the long pendulum system is the least unstable and requires the smallest bandwidth at the plant input for
stabilization (and one might thus say that it is the easiest to control).
However, because this system also possesses the smallest RHP zero it will permit the smallest cart displacement x
bandwidth, and hence, one can argue that the long pendulum system is the hardest to control.
Analogous “intermediate conclusions” can be drawn for the system with the “intermediately sized” pendulum.
A set of simple academic examples (growing in plant and controller complexity) are introduced to illustrate basic
tradeoffs and guide the presentation of the trade studies.
