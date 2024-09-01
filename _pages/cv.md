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
* B.S. in Biotechnology and Business (Accounting), University of Technology Sydney, 2013
* M.S. in Information Technology (Artificial Intelligence), University of New South Wales, 2020
* Ph.D in Computer Science, University of New South Wales, 2023

Work Experience
======
* Postdoctoral Researcher - AI & Cybersecurity, CSIRO's Data61, Current
* PhD Researcher - AI & Cybersecurity, Cybersecurity Cooperative Research Centre, 2020-2023
* Teaching Assistant - AI & Recommendation Systems, UNSW, 2021-2024
* Developer Intern - Machine Learning, Atlassian, 2020
* Commercial Manager, Westpac, 2017-2020
* Sales Excellence Manager, Microsoft, 2016-2017
* Commercial Analyst, Coca Cola Amatil, 2014-2016

Expertise
======
* Deep generative models (Variational Autoencoders, Denoising Diffusion Models)
* Autoregressive models (Transformers, LSTM, RNN, Markov Chains)
* Computer vision 
  * Image generation
  * Layout generation
  * Multi-modal representations (Text-to-image)
* Machine learning security
  * Adversarial robustness
  * Certified robustness

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Skills
======
* Python
* Pytorch Distributed
* Deepspeed
* Docker & Apptainer
* PostgreSQL
* Slurm
* Linux

<!--   
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer for ACM MM (2024), ICDCS (2024) and ACM MSWiM (2024).
* PC Member for PST (2024) and BuildSec (2024)