---
layout: archive
title: "Research & Projects"
permalink: /research-projects/
author_profile: true

---

* [Unsupervised Classification for Drivers’ Interactive Behaviors](#anchor)

* [Path planning for a laser scanning robot system](#anchor2)


### <span id = "anchor">Unsupervised Classification for Drivers’ Interactive Behaviors</span>
* Advisor: Prof. [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), UC Berkeley

<center><img src='/images/unsup.PNG' width="50%" height="50" /></center>
  
In this project, we propose a framework which can unsupervisedly classify interaction types only based on motions (X-Y coordinates) of two vehicles. We propose 3 auxiliary supervised tasks and a combined loss function which could solve the mode collapse problem during unsupervised learning. We find three explainable types of interactions by the proposed model, which brings insight for driver behavior modeling. [Click to View the Paper](http://jiaxiaosong.github.io/files/CVPR_2020_under_review.pdf) (under review of CVPR 2020)

<iframe width="280" height="157" src="https://www.youtube.com/embed/v5ppij0nyvg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### <span id = "anchor2">Generalizable Drivers’ Interactive Pattern Learning</span>
* Advisor: Prof. [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), UC Berkeley
<center><img src='/images/results2.png' width="33%" height="33%" /><img src='/images/scan_result05.png' width="33%" height="33%" /></center>

In this project,  we propose a new task: judge and locate the interactive behaviors based on a pair of vehicles' trajectories. Correspondingly, we propose a framework for the new tasks including labeling rules, data preprocessing and augmentation methods, a neural network structure, loss functions, and metrics. Please refer to the first part of my [intern report] for details. (in preparation for IROS)
