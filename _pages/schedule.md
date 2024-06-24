---
layout: page
permalink: /schedule/
title: Schedule
description: 
nav: true
nav_order: 4
---


All seminars are happening on Thursday 4-5pm (CET), unless the description specifies a different day/time.



---------

**June 27th - [Ganesh Jawahar](https://ganeshjawahar.github.io/)**

Title: Mixture-of-Supernets: Improving Weight-Sharing Supernet Training with Architecture-Routed Mixture-of-Experts

Abstract: 

In this talk, I will present Mixture-of-Supernets, a formulation designed to enhance the expressive power of supernet architectures. We demonstrate that the MoE concept can be utilized to generate flexible weights for subnetworks. Through extensive evaluations aimed at constructing efficient BERT and MT models, we have shown that our supernets can: (i) minimize retraining time, thereby significantly improving NAS efficiency; and (ii) produce high-quality architectures that satisfy user-defined constraints via NAS. This work will be presented at ACL 2024 and can be found here: [https://arxiv.org/abs/2306.04845](https://arxiv.org/abs/2306.04845).

---------

**September 5th - [Linus Eriksson](https://linusericsson.github.io/)**

Title: einspace: Searching for Neural Architectures from Fundamental Operations


Abstract: 

Neural architecture search (NAS) finds high performing networks for a given task. Yet the results of NAS are fairly prosaic; they did not e.g. create a shift from convolutional structures to transformers. This is not least because the search spaces in NAS often aren't diverse enough to include such transformations a priori. Instead, for NAS to provide greater potential for fundamental design shifts, we need a novel expressive search space design which is built from more fundamental operations. To this end, we introduce einspace, a search space based on a parameterised probabilistic context-free grammar. Our space is versatile, supporting architectures of various sizes and complexities, while also containing diverse network operations which allow it to model convolutions, attention components and more. It contains many existing competitive architectures, and provides flexibility for discovering new ones. Using this search space, we perform experiments to find novel architectures as well as improvements on existing ones on the diverse Unseen NAS datasets. We show that competitive architectures can be obtained by searching from scratch, and we consistently find large improvements when initialising the search with strong baselines. We believe that this work is an important advancement towards a transformative NAS paradigm where search space expressivity and strategic search initialisation play key roles.


