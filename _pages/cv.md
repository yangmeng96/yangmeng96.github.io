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
* Ph.D. in Statistics, University of California, Irvine, 2026 (expected)
* M.A. in Statistics, Columbia University, 2020
* B.S. in Statistics, Zhejiang University, 2018

Work experience
======
* Machine Learning & Experimental Design @ Varo Bank, 11/2021 - 08/2022
  * Improved customized customer retention strategies by modeling customer behavior with Markov chains
  * Accelerated the customer acquisition process by 14+% after designing and running an experiment to test the effect of the color changing in the email advertisement, and evaluated A/B Testing results in Tableau
  * Standardized the SQL-to-Tableau pipeline, the new ETL and analysis process are widely used in the company

* Data Science Modeling & Business Analytics @ YipitData, 09/2020 - 10/2021
  * Increased the revenue by 37+% after creating and presenting a tree-based housing price estimation model, and organized bi-weekly meetings with business partners to assess the client needs and research potential features
  * Launched web scraping systems and the monthly reporting system by designing DAGs using AirFlow
  
Skills
======
* Coding
  * Languages: Python (PyTorch, Pandas, Numpy, scikit-learn)
  * Databases: PostgreSQL, MySQL, Redshift, Athena
  * Software: Tableau, AirFlow, R (dplyr, ggplot2, shiny)
* Algorithms
  * Generative Models: Diffusion Models, VAE, GAN, Normalizing-Flows
  * Artificial intelligence: Multimodal Learning, Representation Learning, RNN, CNN, Contrastive Learning
  * AI for Science: Neuroscience, Climate Analysis, Public Health
  * Statistical Learning: Random Forest, Decision Trees, Regression, Boosting, PCA, SVM, Clustering, MCMC

Publications and Preprints
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Projects
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
