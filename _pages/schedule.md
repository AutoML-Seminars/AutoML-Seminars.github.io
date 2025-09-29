---
layout: page
permalink: /schedule/
title: Schedule
description: 
nav: true
nav_order: 4
---


Subscribe to our [calendar](https://calendar.google.com/calendar/u/2?cid=YXV0b21sc2VtaW5hckBnbWFpbC5jb20) for the most recent schedule.

---------

**October 2nd 3:00pm CET - [Carolin Benjamins](https://www.ai.uni-hannover.de/de/institut/team-luhai/benjamins)**

Title: carps: A Framework for Comparing N Hyperparameter Optimizers on M Benchmarks

Abstract: 

Hyperparameter Optimization (HPO) is crucial to develop well-performing machine learning models. In order to ease prototyping and benchmarking of HPO methods, we propose carps, a benchmark framework for Comprehensive Automated Research Performance Studies allowing to evaluate N optimizers on M benchmark tasks. In this first release of carps, we focus on the four most important types of HPO task types: blackbox, multi-fidelity, multi-objective and multi-fidelity-multi-objective. With 3336 tasks from 5 community benchmark collections and 28 variants of 9 optimizer families, we offer the biggest go-to library to date to evaluate and compare HPO methods. The carps framework relies on a purpose-built, lightweight interface, gluing together optimizers and benchmark tasks. It also features an analysis pipeline, facilitating the evaluation of optimizers on benchmarks. However, navigating a huge number of tasks while developing and comparing methods can be computationally infeasible. To address this, we obtain a subset of representative tasks by minimizing the star discrepancy of the subset, in the space spanned by the full set. As a result, we propose an initial subset of 10 to 30 diverse tasks for each task type, and include functionality to re-compute subsets as more benchmarks become available, enabling efficient evaluations. We also establish a first set of baseline results on these tasks as a measure for future comparisons. With carps (https://github.com/automl/CARP-S), we make an important step in the standardization of HPO evaluation.


---------

**October 16th 3:00pm CET - [Jan van Rijn](www.universiteitleiden.nl/en/staffmembers/jan-van-rijn#tab-1)**

Title: Multi-Objective AutoML: Towards Accurate and Robust models

Abstract: 

Machine learning models have to adhere to many requirements. Beyond the need to be accurate and small enough to be deployed on satellite hardware, they need to be robust against various types of domain shifts. Automated machine learning has been successful in supporting data scientists in selecting appropriate machine learning architectures, as well as optimising hyperparameters. By doing so, data scientists can focus their attention on more important tasks. 

During the Horizon TAILOR project, we have seen a demand for AutoML techniques to not only provide solutions that are accurate but also those that are trustworthy according to several relevant criteria. 
Many models are known to be vulnerable to various types of input perturbations, whereas robustness against such deviations is an important criterion of trustworthiness. In this talk, I will summarise various projects we have done towards this goal, which envision AutoML solutions that specifically address the robustness of neural networks, but also include what hyperparameters are important to tune.

