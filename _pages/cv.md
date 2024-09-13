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
* M.Sc. in Computer Science, Concordia University, 2023-2025 (expected)
* B.Sc. in Computer Engineering, Ferdowsi University of Mashhad, 2022
  * Thesis title: "Thesis Title: Lightweight FAQ Answering Bot Using Siamese Networks"

Work experience
======
* Fall 2023 – Present: Graduate Research Assistant
  * Concordia University
  * Duties include: Developing efficient deep learning solutions for high-resolution images, focusing on both theoretical and system-level improvements; self-supervised algorithms for Gigapixel Whole Slide Images (WSI) addressing complex tissue structures and label scarcity

* Spring 2022 – Summer 2023: Machine Learning Researcher
  * Motometrix Inc
  * Duties included: Developed a physics-based simulation for LiDAR sensors, with a primary focus on modeling 'raydrop'; designed a pipeline for processing LiDAR data to generate 3D vehicle assets; created a pipeline for generating 3D models of cities using satellite imagery and OpenStreetMap data; proposed a novel pipeline to detect occlusions for LiDAR sensors

* Fall 2020 – Winter 2022: Machine Learning Engineer
  * ParsTech AI
  * Duties included: Developed virtual try-on GAN models for high-resolution images using knowledge distillation; worked on disentangling and manipulating the latent space of StyleGAN2 to create a facial attribute editor application

* Fall 2020: Machine Learning Intern
  * ParsTech AI
  * Duties included: Developed deepfake image detection models using CNNs, transfer learning, and Fourier domain analysis



Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Skills
======

* Programming
  * Highly skilled in Python
  * Familiar with Java, C/C++, Triton/CUDA

* Frameworks/Libraries
  * PyTorch
  * OpenCV
  * NumPy
  * Pandas
  * Matplotlib
  * scikit-learn
  * Open3D
  * ROS
  * Embree
  * pytest
  * FastAPI
  * Selenium

* Miscellaneous
  * Linux (Ubuntu)
  * Shell (Bash)
  * LaTeX
  * Gazebo
  * Git
  * Jupyter
  * Docker
  * VS Code
  * AWS (EC2)