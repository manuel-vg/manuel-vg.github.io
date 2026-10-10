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
* PhD in Computer Science, Interdisciplinary Doctoral School, University of Warsaw — dissertation submitted
* MSc in Computational Logic, Technical University of Madrid, 2011
* BSs in Computer Systems Engineering, Universidad del Valle, La Paz, 2001

Work experience
======
**Research Scholar**  
Institute of Mathematics, Polish Academy of Sciences (IMPAN), later affiliated with the Faculty of Mathematics, Informatics, and Mechanics, University of Warsaw (MIMUW), Warsaw, Poland  
*Oct. 2021 – Sep. 2025*  
- Research on neural and symbolic methods for natural language reasoning and formal logic, funded through the NCN OPUS 19 project *Hybrydowe modele rozumowania*.

**Software Developer**  
San Calixto Observatory, La Paz, Bolivia  
*Oct. 2017 – Jun. 2018*  
- Designed and developed the “Boletín Sísmico” system, including database (MySQL), backend logic, and user interface using Python.

**Researcher**  
University of Kassel, Formal Methods and Software Verification Group, Kassel, Germany  
*Sep. 2011 – Jul. 2014*  
- Full-time research position focused on model checking and programming in OCaml.

**Research Scholar**  
Technical University of Madrid, COSTA Research Group, Madrid, Spain  
*Nov. 2009 – Feb. 2011*  
- Scholarship-funded research position focused on programming in Prolog.

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
