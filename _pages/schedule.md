---
layout: page
permalink: /schedule/
title: Schedule
description: 
nav: true
nav_order: 4
---


See our [calendar](https://calendar.google.com/calendar/embed?src=automlseminar%40gmail.com) for the most recent schedule. To subscribe, see the [About page](/).

---------


**November 19th 3:00pm CET - [Herilalaina Rakotoarison](https://herilalaina.github.io/)**

Title: An Open-Source Training Dataset for Foundation Models for Hyperparameter Optimization

Abstract: 

Most hyperparameter optimization methods require extensive tuning of their own hyperparameters, often limiting their ability to generalize across different benchmark families. Foundation models for hyperparameter optimization that learn optimization principles from a large collection of optimization trajectories offer a promising alternative, with the potential to outperform manually designed methods across diverse problem classes. However, prior work has either relied on non-public datasets or on purely synthetic data, limiting reproducibility and generalization to real-world problems. As a result, progress in this area has been constrained by the lack of large-scale, real-world, publicly available pre-training data. We introduce BBO-Pile, the first open-source dataset comprising over 500K optimization trajectories evaluated across 3,095 different hyperparameter optimization tasks and global optimization problems for different optimizers, which represents by far the largest public dataset for this task. Using this dataset, we train a family of foundation models at multiple scales, ranging from 2M to 80M parameters and from 200M to 2B training tokens, and study their scaling behavior with respect to compute. Our results demonstrate that large-scale pre-training is a viable and effective approach to imitate hyperparameter optimization methods, paving the way for future research in this direction.

---------

**December 3rd 3:00pm CET - [Hannan Mahadik](https://github.com/HannanJaved)**

Title: TBA

Abstract: TBA

---------

**January 14th 2027 3:00pm CET - [Zhiliang Chen](https://chenzhiliang94.github.io/home/)**

Title: Efficiently Estimating Optimal Hyperparameter Scaling Laws through Power-Law Entropy Search

Abstract: Optimal hyperparameter scaling laws describe how the best hyperparameters for large language model (LLM) training change with model and data scale, enabling practitioners to predict optimal configurations at production scales without expensive large-scale tuning. However, estimating these scaling laws conventionally requires exhaustive grid searches over thousands of training runs, consuming enormous computational resources. We introduce Power-Law Entropy Search (PLES), a computational cost-aware acquisition function built on multi-fidelity Bayesian optimization that efficiently estimates optimal hyperparameter scaling laws through adaptive experimentation. A key innovation in PLES is that it searches for candidates that reduce the overall uncertainty of a scaling law estimate, instead of optimizing a single objective function. At each iteration, PLES selects the candidate configuration that maximally reduces the uncertainty of the scaling law estimates per unit computational cost, naturally favoring informative small-scale experiments. We evaluate PLES on synthetic benchmarks, surrogate models fitted to real LLM training data, and actual LLM pre-training runs. Across all settings, PLES converges to accurate optimal hyperparameter scaling laws using as little as one-tenth of the computational budget required by conventional grid search and other baselines.

---------

**January 28th 2027 3:00pm CET - [Per Kristian Lehre](https://pklehre.github.io/EC-Theory-UoB/Lehre/)**

Title: Automated Design and Analysis of Black-Box Optimisation Algorithms with LLMs

Abstract: The mathematical capabilities of LLMs have improved dramatically. Several long-standing open problems have recently been resolved, and a solution to the Navier-Stokes problem has been claimed. However, these results mostly concern existing mathematical concepts, whereas human mathematicians also invent new concepts and prove statements about them. It is unclear whether LLMs can do the same. Designing an optimisation algorithm and the potential function used to analyse it is exactly this kind of concept invention. Here, we study whether LLMs can simultaneously invent an optimisation algorithm and prove performance guarantees about it. We present a staged agentic pipeline modelled on the research methodology of design and analysis of evolutionary algorithms. The agent proposes black-box optimisation algorithms, and the proof assistant Lean filters out flawed designs. The agent then defines a potential function and proves drift bounds that yield bounds on the expected runtime of the algorithm. All the definitions and theorems constructed by the agent are machine-checked in Lean. At no point in the pipeline are the algorithms compared empirically. On a well-studied problem from the literature (LeadingOnes), the agent rediscovers a known algorithm with expected runtime O(n^2). On a new problem, constructed so that it cannot appear in the LLM’s training data, the agent designs a new algorithm with expected runtime O(n^4), where standard evolutionary algorithms such as the (μ+λ) EA have expected runtime e^Ω(n). For minimisation of integer-valued submodular functions upper bounded by M=n^c, the agent moves beyond evolutionary algorithms and designs a randomised subgradient method on the Lovasz extension and proves an expected runtime of O(n^(2+2c)), which is within a factor n of the best known black-box bounds. To the best of our knowledge, this is the first example of an automated pipeline that designs efficient black-box optimisation algorithms with machine-checked runtime bounds in Lean.

---------





