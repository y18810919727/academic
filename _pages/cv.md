---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /
---
{% include base_path %}

Education
=========

* B.S. in University of Science and Technology Beijing, Computer Science and Technology, 2013.09-2017.07
* Ph.D in University of Science and Technology Beijing, Computer Science and Technology, 2017.09-2023.01

**Research fields**
===================

Intelligent Manufacturing, Dynamical system modeling, Model-based reinforcement learning, Industrial system optimization, Time series analysis, Causal Discovery

Work experience
===============

### Huawei 2012 Academia Sinica-Network Technique Lab &emsp;  Postdoctor &emsp; 2023.01 - 2023.07


Research Topics:

* Network flow modeling,
* Root Cause Identification

### The Hong Kong Polytechnic University (PolyU) CPI &emsp; Postdoctor &emsp; 2023.08 - until now

Research Topics:

* Intelligent Manufacturing
* Industrial AI


Honors
===================

1. Top Ten Academic Stars in University of Science and Technology Beijing, 2023 (PhD Group)
2. ACM-ICPC Asia Regional Contests: **Gold Medal** * 1 (**The only one in USTB**)，Silver Medal * 4 (2015-2017) ACM-ICPC EC-final/China-final: Silver Medal*1, Bronze Medal*1 (2015-2016)
3. The Second prize of the Chinese Electronic Association for technological progress, 2022(Ranked first in the students)
4. The First prize of science and technology of the Chinese Gold Association * 2, (2020, 2023)
5. Honorary title of CCF “Understanding student” in 2016
6. The 7th CCF Certified Software Professional(csp): score: 360( Full score: 500), Rate: Top 1.16%,

Publications
============

<ul>
{% assign pub_reverse = site.publications | reverse %}
{% for post in pub_reverse %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>


Projects & Researches
===================

### 2023/02 - 2023/07 &emsp; Root Cause Analysis for Private Cloud-Network Platform
(Huawei Network lab)
In private cloud platforms, topological relationships between devices and micro-services are always lost seriously. To identify root alarms under incomplete calling graphs, I developed a root cause analysis system based on data-driven causal discovery. The proposed technique uses the causal discovery algorithm to restore the calling chain relationships between different entity types (nearly 90 species) and different entities (200,000 species) from temporal alarm events. Now, the efficiency of the system has been tested the  and it is providing services for an operation and maintenance management system in an airport.
Related theory and techniques: AIOPs; Causal discovery

### 2018/05 - 2022/12 &emsp; Data-based modeling and RL control for complicated industrial system &emsp; PhD project
1. To model industrial systems with long-time delay, nonlinearity, and stochasticity from irregularly sampled offline data, I propose the Ordinary Differential Equation Recurrent State Space Model (ODE-RSSM) based on temporal variational auto-encoder and differential neural networks. The paper is acceptedby the conference AAAI2023.
2. Most adaptive industrial controlling techniques suffer from slow learning and the high cost of trial and error. Based on offline reinforcement learning, I propose an effective pipeline to learn control policy (DDPG) from offline system trajectories and optimize the model parameters in online production. At a copper mine in Zambia, Africa, the proposed technique is employed to control the underflow concentration of deep cone thickener and the tracking error is 20% lower than the manual strategy.
Related theory and techniques: Offline &  Model-based Reinforcement learning, Model Predictive control.

### 2019/10 - 2022/10 &emsp; Intelligent control and decisions for paste backfilling in metal mine
 &emsp; National Key Research and Development Program of China
This project belongs to the National Key Research and Development Program of China. I am a leader of a group of 10 people to develop a B/S paste backfilling management system in mining production.
Functions: Intelligent control, production management, visual detection, and real-time 3D backfilling visualization.
Responsibility: Team management, technical route design, system prototype design, and control algorithm design.

