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
- **University of Maryland**, College Park  
  Intended B.S. in Computer Science (Currently in Letters & Sciences)  
  Aug 2025 – May 2028 (expected)  

- **The Pennsylvania State University**, University Park  
  Transferred, B.S. in Electrical Engineering  
  Aug 2024 – May 2025  
  GPA: 3.94 / 4.00; Dean’s List (two semesters)  

Research Experience
======
- **Research Assistant**, Purdue University — Summer 2025  
  Supervised by Dr. Jingbo Wang and Xuyang Li 
  * Duties included: 	                                                             
    - Extended Soufflé Datalog engine with probabilistic and evidence semantics as a high-performance alternative to Problog using C++.
    - Implemented Marginal Probability Computations in Soufflé.
    - Integrated Sentential Decision Diagram (SDD) into Soufflé for Weighted Model Counting (WMC); optimized Binary Decision Diagram (BDD) variable orderings and SDD vtree structures for efficiency.
    - Built benchmarks and evaluated performance against existing Problog implementations on multiple datasets.
    - Co-first author on a paper in preparation for CAV 2026; collaborator on a paper in preparation for OOPSLA 2026.

Skills
======
* **Tools & Environment**:
  * Linux
  * Git
  * LaTeX
* **Programming Languages**: C++, Python, Java

Research Interests
=====
* Artificial Intelligence
* Formal Methods
* Causal Inference
* Cognitive Science

Coursework
=====
* In Progress: CMSC132 (Data Structures), CMSC250 (Discrete Math), MATH241 (Calculus III)  
* Completed: CMSC131 (via placement), MATH140/141 (Calculus I–II, A), PHYS161 (Physics I, A)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
