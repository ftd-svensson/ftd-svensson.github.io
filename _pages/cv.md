---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Full Resume

**English:** [View Resume (PDF)](/files/ftd-Resume-ENG.pdf)  
**Swedish:** [View Resume (PDF)](/files/ftd-Resume-SWE.pdf)

## Education

### Master of Science in Engineering — Game and Software Engineering
*Blekinge Institute of Technology · 2026*

Focus on **C++ software engineering, 3D systems, and performance optimization**.

Master's thesis conducted at **[HINTS](https://www.bth.se/forskningsmiljoer/hints-human-centered-intelligent-realities)**, investigating material properties and spatial audio in virtual environments.

### Upper Secondary Technical Degree
*Ehrensvärdska Gymnasiet · 2016*

## Work Experience

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Skills

- **Programming:** C/C++, C#, Python, ARM/Intel Assembler, Javascript
- **3D & Graphics:** 3D systems, real-time rendering
- **Tools:** Unreal Engine, Git, Visual Studio, Windows, Linux
- **Other:** Performance optimization, Basic Machine learning, Basic AI

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
