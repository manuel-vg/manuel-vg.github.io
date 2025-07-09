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
* Ph.D in Computer Science & Linguistics, Interdisciplinary Doctoral School, University of Warsaw, 2025 (expected)
* M.S. in Computational Logic, Technical University of Madrid, 2011
* B.S. in Computer Systems Engineering, Universidad Privada del Valle, La Paz, 2001

Work experience
======
**Research Scholar**  
Institute of Mathematics, Polish Academy of Sciences (IMPAN), Warsaw, Poland  
*Oct. 2021 – Sep. 2024*  
- Scholarship-funded research position focusing on deep learning and Python programming.

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
