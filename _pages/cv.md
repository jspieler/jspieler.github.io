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
* 10/2019 - 04/2022: M.Sc. in Automotive Engineering, University of Stuttgart
* 10/2016 - 09/2019: B.Eng. in Mechanical Engineering, Baden-Wuerttemberg Cooperative State University (DHBW)

Work experience
======
* 10/2024 - Present: Research Assistant, Autonomous Intellgent Systems, University of Bonn
* 04/2023 - 06/2024: Adjunct Lecturer
  * Teaching of a Python lecture for undergraduates (30 students)
  * Teaching of a lecture on safety and validation of deep learning systems (with a focus on autonomous driving) for undergraduates (30 students)
  * Member of the examination committee for the Bachelor’s examination in the Data Science degree programme
* 05/2022 - 09/2024: Software Engineer Autonomous Driving
  * Design, implementation and testing of a plattform for the validation of autonomous driving functionalities
* 10/2021 - 04/2022: 
  * Researchon reinforcement learning algorithms for continuous action spaces
  * Research on reward shaping for multi-objective optimization problems
  * Development of an energy management stategy for a plug-in hybrid electric vehicle based on reinforcement learning
* 04/2021 - 09/2021: Intern Robotics & Navigation Research Department
  * Research, development and implementation of path planning algorithms for robotic lawn mowers
  * Design and integration of GNSS sensors on the navigation system of a Boston Dynamics Spot, including implementation of trajectory control
* 12/2019 - 02/2021: Student Research Assistan
  * Preparation and support of teaching activities for the lectures Embedded Controller, Automotive Mechatronics and Data Networks
* 09/2016 - 09/2019: Cooperative Student
  * Research on cooling systems for electrical drives
  * Simulation of electrical drives including coupling of thermal and driving models
  * Different research projects on automatic transmissions for passenger cars
  
Skills
======
* Programming languages: Python, C++, JavaScript 
* Frameworks & tools: React, MySQL, ROS, PyTorch, TensorFlow, Git, Linux, Docker, and a bunch of Python packages
* Software Engineering: CI/CD, Unit Testing, OOP, Software Design

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
  
