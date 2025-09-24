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
* 2021~2024: PhD ABD
  * Department of Computer Science, Hong Kong Baptist University
  * Duties included: causal model evaluation, hetergeneous data, medical data
  * Supervisor: Yiuming CHEUNG (YMC, A member of European Academy of Sciences and Arts, IEEE Fellow, AAAS Fellow, RGC Senior Research Fellow, Changjiang Scholars)
* Computer Science and Technology, M.S. in Beijing, Beijing Institute of Technology, 2018-2021
* Internet of Things Engineering, B.S. in Qingdao, Qingdao University, 2014-2018

Work experience
======
* 2024 ~ 2025: Engineer
  * Institute of Computing Technology, Chinese Academy of Science
  * Duties includes: Computaional Evaluation
  
Skills
======
* Causality
  * Identify treatment effect on DAG with hidden common causes
  * When and why to use causal inference
* Game theory
* Discreate math

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
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
