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
* Master of Science in Engineering: Game and Software Engineering
Blekinge Institute of Technology - 2026
Focus on C++ software engineering, 3D systems, and performance optimization.
Master Thesis at HINTS where I investigated material properties and spatial audio in virtual environments.
* Upper secondary technical degree

Work experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
