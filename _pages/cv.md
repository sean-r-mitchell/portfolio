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
* M.S. in Electrical Engineering, University of Alabama in Huntsville, 2026 (Expected)
  * Minor: Mathematics
  * Focus: Dynamical Systems, Chaos Theory, and Machine Learning
  * Thesis: Influence of Entropy and Periodicity in Neural Network Training
      * Advisor: Dr. Aubrey Beal
      * ``Deep neural networks typically utilize psuedo-random number generation to populate the default states of neurons. Shown is an alternative approach that utilizes the non-linear dynamics that are present in one-dimensional mappings that exhibit chaos. These dynamics can be used to initialize the neurons and show equivalent or greater performance than traditional algorithms.``
* B.S. in Electrical Engineering, University of Alabama in Huntsville, 2020
  * Minor: Computer Science
  * Focus: Mechatronics & Control Theory

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
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
  
