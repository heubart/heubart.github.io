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
* B.S. in Electrical and Electronics Engineering, International Islamic University, 2022


Work experience
======
* Spirng and Autumn 2023: Teaching Assistant 
  * Faculty of Science and Engineering, International Islamic University, 2022
  * Duties included: Tagging issues

* Autumn 2022: Research Assistant (Remote)
  * King Fahd University of Petroleum and Minerals
  * Duties included: Control and Optimization
  * Supervisor: <a href="https://scholar.google.com/citations?user=IrQqEgIAAAAJ&hl=en"> Dr. Md Shafiullah</a> (KFUPM)
  
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
  <ul>{ for post in site.publications }
    { include archive-single-cv.html }
  { endfor }</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
