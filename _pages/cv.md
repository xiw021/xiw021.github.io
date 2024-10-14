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
* Ph.D in Political Science with a Specialization in Computational Social Science, University of California San Diego, 2026 (expected)
* M.S. in Electrical Engineering, Columbia University, 2018
* B.S. in Electrical Engineering, Tianjin University, 2017

Work experience
======
* December 2018 - August 2020: Data Science Research Associate
  * Columbia Law School
  * Supervisor: Benjamin L. Liebman
  
Skills
======
* Python(Scikit-learn, Pandas, TensorFlow, Selenium), R, SQL(PostgresSQL, MySQL), Bash, Git, LaTeX, Neo4j, MATLAB. 

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

