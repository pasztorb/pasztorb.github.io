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
* Ph.D in Machine Learning, ETH AI Center (ETH Zurich), 2025 (expected)
  * Topic: Multi-agent Learning in General-sum Games
  * Supervisors: Prof. Dr. Andreas Krause, Prof. Dr. Sven Seuken
* M.Sc. in Data Science, ETH Zurich, 2020
* B.Sc. in Mathematics with Economics, University College London, 2018

Work experience
======
* Data Scientist (2020 October - 2022 August)
  * QuantumBlack, AI by McKinsey & Company (Zürich, Switzerland)
  * Industries: Automotive, Telecommunication, Mining, Pharmaceutical, Retail
  * Functions: Pricing, Marketing, Due Diligence, Forecasting
* Research Assistant (2019 February - 2020 February)
  * Social Networks lab, ETH Zurich (Zürich, Switzerland)
  * Supervisor: Prof. Dr. Ulrik Brandes
  * Research topic: Graph Embedding & Visualization


Publications
======
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic Achievements
======
* Finalist, MeltingPot competition (NeurIPS 2023)
  * Top 6 out of 117 teams
  * Developed a Multi-Agent RL system to learn in challenging social dilemma environments
  * Techniques and frameworks used: IMPALA, A2C, PopArt, reward shaping, curriculum learning, RLLib
* 2nd place, Computational Social Choice Competition (IJCAI 2023)
  * Proposed a provably optimal and efficient voting rule for best-k candidate voting problem

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
