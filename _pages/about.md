---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am David D. Nguyen, a researcher in artificial intelligence and machine learning, with a particular focus on generative models and their applications in cybersecurity. 
My PhD was completed at the University of New South Wales under the guidance of Salil Kanhere (UNSW), Surya Nepal (CSIRO) and David Liebowitz (Penten).
I have published papers at AAAI and ACM Multimedia that focus on generative modelling of images, layouts and documents.

Currently I am at CSIRO's Data61, Australia's National Research Laboratory, specializing in theoretical and applied machine learning in the cyber security domain. 
My recent research interests are adversarial purification, adversarial robustness and text-to-speech recognition.
If you are interested in collaborating or a PhD research position at CSIRO, please feel free to contact me at (d DOT nguyen AT csiro DOT au).

Recent News
======

### 10/12/23 - Paper accepted into AAAI 2024.
Our latest paper introduces Multiple Hypothesis Dropout (MH-Dropout), a novel variant of dropout that converts a single-output function into a multi-output function. Check out our paper [here](https://ojs.aaai.org/index.php/AAAI/article/view/29358) and code [here](https://github.com/dngu7/multiple-hypothesis-dropout)!
The illustration below depicts a *Mixture of Multiple Output functions (MoM)*.

![diagram](/images/hierarchydiagram.png)

This novel technique employ subnetworks from a base neural network to estimate the parameters of multi-modal Gaussian distributions. 
Using this technique, we propose an improved VQGAN that generates higher quality images using a significantly smaller codebook. 
The samples below were generating using only 4-64 codebook entries.

![mhdimage](/images/mhd-images.png)


### 22/5/22 - Best paper award from UNSW.
Very honoured to have won the Norman Foo Memorial Best PhD Paper Award from [UNSW](https://www.unsw.edu.au/engineering/our-schools/computer-science-and-engineering/student-life/prizes-awards)! 
Check out the paper [here](https://dl.acm.org/doi/10.1145/3474085.3475525) which introduces a model that generate layouts with a new multiple choice learning technique that avoids modal collapse and prediction averaging.

![layoutpreview](/images/layout_preview.png)

