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
* M.S. in Beijing, Peking University, 2022
* B.S. in Tianjin, Tianjin University, 2019

Work experience
======
* Fall 2022: Management Trainee
  * Bank of China (Head Office)
  * Duties includes: Updates and improvements to template

* Summer 2021: Intern Algorithm Engineer
  * Tencent
  * Duties included: Merging pull requests

* Winter 2020: Intern Algorithm Engineer
  * Microsoft 
  * Duties included: Tagging issues
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
