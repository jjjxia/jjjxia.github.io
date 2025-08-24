---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Intended to major in CS, University of Maryland, 2028(expected)

Work experience
======
* Summer 2025: Research Assistant
  * Purdue University
  * Duties included: 	                                                             
    - Extended the Soufflé Datalog engine to support probabilistic and evidence semantics to support probabilistic computations as a high-performance alternative to Problog using C++.
    - Implemented the task of Marginal Probability Computations in Soufflé.
    - Integrated Sentential Decision Diagram (SDD) into Soufflé to perform Weighted Model Counting (WMC); optimized Binary Decision Diagram (BDD) variable orderings and SDD vtree structures for efficiency.
    - Built benchmarks and evaluated performance against existing Problog implementations on multiple datasets.
    - Preparing the submission to CAV, 2026.

  * Supervisor: Dr. Jingbo Wang, Xuyang Li
  
Skills
======
* Tools & Environment:
  * Linux
  * Git
  * LaTex
* Programming Languages: C++, Python, Java

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
