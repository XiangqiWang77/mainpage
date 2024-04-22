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
=========

* Ph.D in Computer Science, University of Notre Dame, 2024
* B.S. in Data Science, University of Science and Technology of China, 2020

Work experience
===============

* Fall 2023: Research Assistant

  * Fair Online Influence Maximization
  * Duties includes: Theoretical proof and experimental design
  * Supervisor: Dr. Huazheng Wang and Dr. Jian Kang
* Fall 2022: Research Assistant

  * University of Science and Technology of China
  * Duties included: Design novel negative sampling method for graphical recommender system
  * Supervisor: Professor Qi Liu
* Summer 2021: Research Assistant

  * Foxit Company
  * Duties included: Design multimodal text-video alignment and retrieval model.
  * Supervisor: Professor Xu Tong

Skills
======

* Python (Pytorch, PyG), MATLAB, C++

Publications
============

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
=====

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
========

<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======================

* Served as KDD reviewer for 2024.
