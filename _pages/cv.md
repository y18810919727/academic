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

Biography
=========

Dr. Zhaolin Yuan is currently a Distinguished Associate Professor at the School of Intelligent Science and Technology, University of Science and Technology Beijing (USTB). He received his bachelor's degree in Computer Science and Technology from USTB in 2017 and his Ph.D. in Computer Science from USTB in 2023. In 2023, he conducted postdoctoral research at Huawei's 2012 Central Research Institute - Network Technology Laboratory, and he will begin his postdoctoral work in the Department of Industrial and Systems Engineering (ISE) at The Hong Kong Polytechnic University in 2024.
Dr. Yuan has led multiple research projects in the fields of intelligent manufacturing and intelligent mining. He spearheaded the independent development of the "Intelligent Control and 3D Visualization System for Paste Backfill" and the "Auxiliary Decision-Making System for Mineral Processing Plants," generating cumulative economic benefits of over 40 million RMB across three domestic and international mining companies.
He has published more than 10 papers in top-tier artificial intelligence conferences (including AAAI) and internationally recognized high-impact journals, such as IEEE TNNLS, IEEE TII, IEEE JAS, Acta Automatica Sinica, and Tunnelling and Underground Space Technology. Additionally, he has been granted over 10 patents and software copyrights.
His research interests include intelligent mining, intelligent manufacturing, large language model applications, industrial world models, industrial system optimization, and reinforcement learning.

Work experience
===============
## 2024.12 - until now &emsp; School of Intelligent Science and Technology, University of Science and Technology Beijing &emsp; Associate professor

## 2023.08 - 2024.12 &emsp; The Hong Kong Polytechnic University CPI lab &emsp; Postdoctor 
Research Topics: Intelligent Manufacturing; Industrial AI

## 2023.01 - 2023.07 &emsp; Huawei 2012 Network Technique Lab &emsp; Researcher 
Research Topics: Network Flow Modeling; Root Cause Identification

**Research fields**
===================

Intelligent Mining, Intelligent Manufacturing, LLM Applications, Industrial World Model, Industrial Systems Optimization, and Reinforcement Learning, etc.  

Education
=========
* 2017.09-2023.01 &emsp; Ph.D &emsp;Computer Science and Technology &emsp; University of Science and Technology Beijing
* 2013.09-2017.07 &emsp; B.S. &emsp;Computer Science and Technology &emsp; University of Science and Technology Beijing

Honors
===================

1. 2023 Second Prize for Scientific and Technological Progress by the Chinese Institute of Electronics: Key Technologies and Applications for Simulation and Prediction of Mine Backfill Process.
2. 2023 First Prize for Science and Technology by the China Gold Association: Research and Application of Intelligent Visualization Management and Control for Paste Backfill in Metal Mines Using Total Tailings.
3. 2020 First Prize for Science and Technology by the China Gold Association: Research and Application of Precision Control Technology in Mineral Processing Based on Big Data Analysis.
4. 2023 Top Ten Academic Stars (Doctoral Category) at the University of Science and Technology Beijing.
5. 2015-2017, ACM-ICPC Asia Regional Contests: 1 Gold Medal, 4 Silver Medals; China Final: 1 Silver Medal.
6. 2016 CCF Outstanding Undergraduate Student Honorary Title.

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

Academic Services
===================
Reviewer

* IEEE International Conference on Robotics and Automation
* International Journal of Control, Automation and Systems
