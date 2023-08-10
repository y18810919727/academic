---
layout: archive
title: "个人简历"
permalink: /cv_ch/
author_profile: true
redirect_from:
  - /resume-ch
  - /cv_ch.html
---
{% include base_path %}

Education
=========

* 本科，计算机科学与技术，北京科技大学, 2013.09-2017.07
* 博士，计算机科学与技术，北京科技大学, 2017.09-2023.01

Work experience
===============

### Huawei 2012 Academia Sinica-Network Technique Lab----Post Doctor

**Time**

- 2023.01-2023.07:

Research Topics:

* Network flow modeling,
* Root Cause Identification

### [The Hong Kong Polytechnic University (PolyU)](https://www.polyu.edu.hk/)----Post Doctor

**Time**

- 2023.08 - Now

Research Topics:

* Intelligent Manufacturing
* Industrial AI

**Research fields**
===================

Intelligent Manufacturing, Dynamical system modeling, Model-based reinforcement learning, Industrial system optimization, Time series analysis, Causal Discovery

Publications
============

<ul>
{% assign pub_reverse = site.publications | reverse %}
{% for post in pub_reverse %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
=====

<ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
========

<ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======================

* Currently signed in to 43 different slack teams
