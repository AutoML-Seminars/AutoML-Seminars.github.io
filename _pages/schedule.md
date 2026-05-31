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

**June 11th 4:00pm CET - [David Holzmüller](https://dholzmueller.github.io/)**

Title: TabICLv2: A better, faster, scalable, and open tabular foundation model

Abstract: 

Tabular foundation models, such as TabPFNv2 and TabICL, have recently dethroned gradient-boosted trees at the top of predictive benchmarks, demonstrating the value of in-context learning for tabular data. We introduce TabICLv2, a new state-of-the-art foundation model for regression and classification built on three pillars: (1) a novel synthetic data generation engine designed for high pretraining diversity; (2) various architectural innovations, including a new scalable softmax in attention improving generalization to larger datasets without prohibitive long-sequence pretraining; and (3) optimized pretraining protocols, notably replacing AdamW with the Muon optimizer. On the TabArena and TALENT benchmarks, TabICLv2 without any tuning surpasses the performance of the current state of the art, RealTabPFN-2.5 (hyperparameter-tuned, ensembled, and fine-tuned on real data). With only moderate pretraining compute, TabICLv2 generalizes effectively to million-scale datasets under 50GB GPU memory while being markedly faster than RealTabPFN-2.5. We provide extensive ablation studies to quantify these contributions and commit to open research by first releasing inference code and model weights at this https URL, with synthetic data engine and pretraining code to follow.


---------

**June 18th 3:00pm CET - [Difan Deng](https://www.linkedin.com/in/difan-deng-93013b1b3)**

Title: TBA

Abstract: TBA

---------


**July 16th 3:00pm CET - [Amir Balef](https://www.balef.me/)**

Title: Is One Layer Enough? Understanding Inference Dynamics in Tabular Foundation Models

Abstract: 

Transformer-based tabular foundation models (TFMs) dominate small to medium tabular predictive benchmark tasks, yet their inference mechanisms remain largely unexplored. We present the first large-scale mechanistic study of layerwise dynamics in 6 state-of-the-art tabular in-context learning models. We explore how predictions emerge across depth, identify distinct stages of inference, and reveal latent-space dynamics that differ from those of language models. Our findings indicate substantial depthwise redundancy across multiple models, suggesting iterative refinement with overlapping computations during inference stages. Guided by these insights, we design a proof-of-concept, looped single-layer model that uses only 20% of the original model’s parameters while achieving comparable performance. The code is available at https://github.com/amirbalef/is_one_layer_enough.

---------





