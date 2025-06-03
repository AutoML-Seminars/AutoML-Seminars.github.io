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

**June 5th 3:00pm CET - [Lennart Schneider](https://www.slds.stat.uni-muenchen.de/people/schneider/)**

Title:  Hyperband-based Bayesian Optimization for Efficient Black-box Prompt Selection

Abstract: 

Optimal prompt selection is a key factor for good performance of large language models (LLMs) on downstream tasks. However, in black-box settings, where models are only accessible via APIs, automated selection becomes a combinatorial, gradient-free optimization problem with high evaluation costs. We introduce HbBoPs, a framework that integrates a structural-aware Gaussian process surrogate with Hyperband as a multi-fidelity scheduler for sample-efficient black-box prompt selection. By representing prompts through embeddings of instructions and exemplars as modular components, our surrogate captures structural similarities across prompts. Hyperband allows for adaptively allocating computational budget, evaluating prompts at varying fidelity levels, and strongly reducing the number of full prompt evaluations. We validate our approach on ten datasets across three LLMs and demonstrate consistent improvements over state-of-the-art baselines and competitors. This work broadens the scope of AutoML by extending multi-fidelity Bayesian optimization, traditionally applied to hyperparameter or neural architecture search, to structured, high-cost decision spaces in modern NLP.


---------

**June 19th 3:00pm CET - [David Salinas](https://geoalgo.github.io/)**

Title:  Tuning LLM Judge Design Decisions for 1/1000 of the Cost

Abstract: 

Evaluating Large Language Models (LLMs) often requires costly human annotations. To address this, LLM-based judges have been proposed, which compare the outputs of two LLMs enabling the ranking of models without human intervention. While several approaches have been proposed, many confounding factors are present between different papers. For instance the model, the prompt and other hyperparameters are typically changed at the same time making apple-to-apple comparisons challenging.In this paper, we propose to systematically analyze and tune the hyperparameters of LLM judges. To alleviate the high cost of evaluating a judge, we propose to leverage multi-objective multi-fidelity which allows to find judges that trades accuracy for cost and also reduce significantly the cost of the search. Our method identifies judges that not only outperform existing benchmarks in accuracy and cost-efficiency but also utilize open-weight models, ensuring greater accessibility and reproducibility.

