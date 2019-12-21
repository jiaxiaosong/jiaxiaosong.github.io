---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

* [Unsupervised Classification for Drivers’ Interactive Behaviors](#anchor)

* [Generalizable Drivers’ Interactive Pattern Learning](#anchor2)

* [Sentiment Classification with Modeling of Users’ Characteristics](#anchor3)

* [Hot Topic Detection on Early Stage by Survival Theory](#anchor4)

### <span id = "anchor">Unsupervised Classification for Drivers’ Interactive Behaviors</span>
* Advisor: Prof. [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), UC Berkeley

<center><img src='/images/unsup.PNG' width="50%" height="50" /></center>
  
In this work, we propose a framework which can unsupervisedly classify interaction types only based on motions (X-Y coordinates) of two vehicles. We propose 3 auxiliary supervised tasks and a combined loss function which could solve the mode collapse problem during unsupervised learning. We find three explainable types of interactions by the proposed model, which brings insight for driver behavior modeling. 

[Click to View the Paper](http://jiaxiaosong.github.io/files/CVPR_2020_under_review.pdf)

<iframe  width="178" height="100" src="https://www.youtube.com/embed/v5ppij0nyvg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### <span id = "anchor2">Generalizable Drivers’ Interactive Pattern Learning</span>
* Advisor: Prof. [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), UC Berkeley

<center><img src='/images/task1.png' width="50%" height="50" /></center>

In this work,  we propose a new task: judge and locate the interactive behaviors based on a pair of vehicles' trajectories by supervised learning. Correspondingly, we propose a framework for the new task including labeling rules, data preprocessing and augmentation methods, a neural network structure, loss functions, and metrics. Please refer to the first part of my [intern report] for details.

<iframe width="560 " height="315" src="https://www.youtube.com/embed/Pyf_ubAip5E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/M3dbjGGZZ_k" frameborder="0" allow="accelerometer; autoplay;encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### <span id = "anchor3">Sentiment Classification with Modeling of Users’ Characteristics</span>
* Advisor: Prof. [Xiaofeng Gao](http://www.cs.sjtu.edu.cn/~gao-xf/), Shanghai Jiao Tong University

<center><img src='/images/senti.png' width="50%" height="50" /></center>

Sentiment analysis for textual contents has attracted lots of attentions. However, most existing models only utilize the target text to mine the deep relations from text representation features to sentiment values, ignoring user's historicalally published texts, which also contain much valuable information. Correspondingly, we propose SentiMem, a new sentiment analysis framework that incorporates user's historical texts to improve the accuracy of sentiment classification. 

In SentiMem, to exploit users' interests and preferences such as dog person, football fan, and foodie hidden in the texts, we adopt SenticNet to capture the concept-level semantics; as for users' temperaments like optimism, peevishness, and pessimism, we combine multiple sentiment lexicons with multi-head attention mechanism to extract users' diverse characters. Then, we design two memory networks: Interests Memory Network and Temperaments Memory Network to store information about users' interests and temperaments respectively.

[Click to View the Paper](http://jiaxiaosong.github.io/files/DASFAA_2020_in_submission.pdf)

### <span id = "anchor4">Hot Topic Detection on Early Stage by Survival Theory</span>



[Click to View the Paper](http://jiaxiaosong.github.io/files/TKDE_major_revision.pdf)
