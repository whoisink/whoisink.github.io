---
layout: archive
title: "Portfolio"
permalink: portfolio/portfolio/
author_profile: true
---

{% include base_path %}

** **

Recognitions
======
* Chinese national scholarships for postgraduate students
* Outstanding graduate award of the China Three Gorges University
* Outstanding thesis award of the China Three Gorges University

** **

Research Project Participant
======
* **National Social Science Fund of China (grant number: 23BJL037; funding amount: CNY 200000)**: Research on the Application of Big Data and Deep Learning Methods in Credit Debt Default Risk Warning Management

* **Natural Science Foundation of Hubei Province (grant number: 2021CFB175; funding amount: CNY 80000)**: Research on the Dynamic Warning of Stock Price Crash Risk Based on Machine Learning

* **Natural Science Foundation of Yichang City (grant number: A22-3-011; funding amount: CNY 30000)**: Research on the Forward Trading System for Citrus in Yichang Region

** **

Chinese computer software copyright holder
======
* A systematic financial risk monitoring system based on deep learning (Registration number: 2023SR0324321)
* An instantaneous GDP forecasting software based on dynamic factor model (Registration number: 2022SR0773792)

** **

Journal Peer Reviewer
======
* Information Processing and Management
* Financial Innovation


{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
