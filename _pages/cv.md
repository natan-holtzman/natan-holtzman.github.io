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
* B.S. with Honors in Geological Sciences, University of North Carolina at Chapel Hill, 2016
* PhD in Earth System Science, Stanford University, 2024

Experience
======
* 2024-present: Senior Member of Technical Staff at The Aerospace Corporation (El Segundo, CA)
  * Physical Sciences Laboratories - Microelectronics Technology Department
* Summer 2023: Data Science Intern at The Aerospace Corporation (El Segundo, CA)
  * Developed algorithms for state estimation and uncertainty quantification in satellite position/navigation/timing
* 2018-2024: Graduate Researcher at Stanford Remote Sensing Ecohydrology Lab (Stanford, CA)
  * Developed spatiotemporal statistical methods to interpret global microwave remote sensing data
  * Built a Bayesian model-data fusion algorithm to combine satellite observations with computational models of water flow in plants and soil
  * Developed a novel model of plant water use based on classical reinforcement learning
  * Coordinated and carried out a week-long field campaign to measure plant water stress in a forest
  * Supervisor: Prof. Alexandra Konings
* 2016-2018: Research Associate at UNC Institute for the Environment (Chapel Hill, NC)
  * Modified the precipitation and soil modules within a climate model to simulate snowmelt-driven runoff more accurately
  * Developed interactive web app to visualize climate model output
  * Worked with civil engineering researchers to study effects of climate model uncertainty on future hydropower scenarios
  * Supervisor: Prof. Tamlin Pavelsky
  
Skills
======
* Python
* Julia
* R

Awards
======
* FINESST (Future Investigators in NASA Earth and Space Science and Technology), a 3-year graduate fellowship
* Colonel Robinson Scholarship, a 4-year full-tuition scholarship to UNC-Chapel Hill for students in STEM fields

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
