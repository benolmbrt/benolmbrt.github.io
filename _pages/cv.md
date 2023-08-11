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
* M.S. in Image & Data, University of Strasbourg, 2020
* Biomedical Engineering Degree, Télecom Physique Strasbourg, 2020
* Ph.D on _**Uncertainty for Deep Learning based medical image segmentation**_, Grenoble Alpes University, 2024 (expected)

Work experience
======
* October 2020-May 2021: Research Enginner
  * Pixyl 
  * Duties included:
      - Development of DL models for classification/segmentation of 3D MRI
      - Calibration of neural networks probability estimates
      - Development of Data Augmentation tools 

* Mars-August 2020: Graduation Engineering project
  * Pixyl 
  * Duties included:
      - Deep Learning approaches for unsupervised anomaly detection in 3D medical images
        
* May-August 2019: Research Internship
  * Amsterdam AMC
  * Duties included:
    - Development of a Generative Adversarial Network (GAN) for CT to CTA translation
    - Application to brain vessel segmentation
   
* June-July 2018: Engineering Internship
  * Amiens-Picardie University Hospital - Nuclear Medicine Department
  * Duties included:
    - Implementation of a User-Interface for PET image reconstruction
  
Skills
======
* Deep Learning / Machine Learning 
  * Python, PyTorch, Pytorch Lightning, TorchIO, sklearn, Deep Graph Library, MONAI
    
* Medical Image processing
  * Nibabel, AnTS, c3d 
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
