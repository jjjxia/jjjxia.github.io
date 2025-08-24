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
* **University of Maryland** — Intended B.S. in Computer Science  
  *Aug 2025 – May 2028 (expected)*  

* **The Pennsylvania State University** — B.S. in Electrical Engineering  
  *Aug 2024 – May 2025*  
  - GPA: 3.94 / 4.00  
  - Dean’s List (two semesters)
Research experience
======
* Summer 2025: Research Assistant
  * Purdue University
  * Duties included: 	                                                             
    - Extended the Soufflé Datalog engine to support probabilistic and evidence semantics to support probabilistic computations as a high-performance alternative to Problog using C++.
    - Implemented the task of Marginal Probability Computations in Soufflé.
    - Integrated Sentential Decision Diagram (SDD) into Soufflé to perform Weighted Model Counting (WMC); optimized Binary Decision Diagram (BDD) variable orderings and SDD vtree structures for efficiency.
    - Built benchmarks and evaluated performance against existing Problog implementations on multiple datasets.
    - Co-first author on a paper in preparation for CAV 2026; collaborator on a paper in preparation for OOPSLA 2026.

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
