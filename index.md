---
layout: home
title: CS-593
nav_exclude: true
seo:
  type: Course
  name: 'Microarchitecture Security'

toc: true
toc_label : "On this page"
toc_hmin: 2
toc_hmax: 6
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }



This course will focus on the interaction of computer security and computer architecture. We will start with the basic architectural background: caches and memory hierarchy, out-of-order execution, speculative execution, and branch prediction. Then we will discuss fundamental system security concepts such as isolation, memory safety, side- and covert-channels, etc. This gives us the necessary background to dive deeper into understanding of how microarchitecture can be exploited to leak information. We will discuss the classic and recent attacks that leverage different architectural structures/components which include caches, branch prediction, DVFS, DRAM, and accelerators/FPGAs. We will then cover high-performance architectural solutions to mitigate those attacks. We will also talk about fundamentally secure approaches and architectures such as constant-time programming, capability-based architectures, and information flow tracking. Finally, we will discuss how architecture can provide efficient support for security and privacy, where we talk about solutions such as Trusted-Execution Environments (TEEs) and architecture support for memory safety and isolation.




## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}


## Prerequisites
Undergraduate Computer Architecture (CS250 or equivalent). We will review most of the needed architectural background. 

## Meetings
Lectures are Tu/Th from 13:30 to 14:45 at REC 103{:target="_blank"}.



## Textbook
This will be mostly a paper reading course, but we will do some readings from the following textbook.
"Principles of Secure Processor Architecture Design", Jakub Szefer
This is part of the outstanding Synthesis Lectures series, which can be found here: Synthesis Lectures on Computer Architecture. Those books will be free to access while you are on the Purdue domain. There are so many great references there (including another security book by Ruby Lee), any number of which would be useful for research in architectural security.
<!-- You will get more out of lecture if you have completed the pre-class reading. 
We try to be clear about what is okay to skim and what will be helpful to read deeply (See [Agenda](#agenda-tentative)). -->


## High-Level Course Outline
 - Introduction
 - Computer Architecture background
 - Fundamental Security concepts
 - Traditional Side-Channel attacks and defenses
 - Transient execution attacks and defenses
 - Rowhammer attacks and defenses
 - Physical Side-Channel attacks and defenses
 - Some more general defense approaches
 - Fundamentally secure architectures/approaches

## Assessments
 - Research Project: 40%
 - Programming Assignments: 20%
 - Midterm: 20%
 - Paper Presentations: 10%
 - Online Quizzes (for readings): 10%

## Agenda (Tentative)

{% for module in site.modules %}
{{ module }}
{% endfor %}

