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
* M.S. in Beijing, Beijing Institute of Technology, 2021
* B.S. in Qingdao, Qingdao University, 2018

Work experience
======
* 2024 ~ ?: Engineer
  * Institute of Computing Technology, Chinese Academy of Science
  * Duties includes: Computaional Evaluation
  * Supervisor: Jianfeng ZHAN

* 2021~2024: PhD student
  * Hong Kong Baptist University
  * Duties included: medical data, hetergeneous data, causality
  * Supervisor: Xian YANG, Yike GUO, Yiuming CHEUNG, Bo HAN
  
Skills
======
* Causality
  * Identify treatment effect on DAG with hidden common causes
  * when and why to use causal inference
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
