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

**June 18th 3:00pm CET - [Difan Deng](https://www.linkedin.com/in/difan-deng-93013b1b3)**

Title: Neural Attention Search, Sub-Layer Level Architecture Search

Abstract: 

The quadratic computational complexity of softmax attention becomes a bottleneck in long-context scenarios. Previous sparse attention methods mostly follow fixed rules to sparsify attention maps, whereas the success story of neural architecture search in the era of convolutional neural networks (CNNs) did not carry over to the transformer era. In this talk, we show that the attention map can be considered a one-shot architecture search space, which allows us to search for a cheaper attention operation that adaptively fits the current input context jointly with the model weights. We further introduce two search space designs that measure the information contained within each token in the input context, and 1) assign different sparse attention operations to those tokens with Neural Attention Search to reduce KV cache size while preserving model performance, 2) assigning cheaper linear attention or more expensive softmax attention operations to those tokens with Neural Attention Search-Linear to design a token-level hybrid architecture with better long-context retrieval ability at lower computational costs. We hope that this work provides further insights into sub-layer level NAS search space design, paving the way towards more efficient and scalable inference with large language models.

---------


**July 16th 3:00pm CET - [Amir Balef](https://www.balef.me/)**

Title: Is One Layer Enough? Understanding Inference Dynamics in Tabular Foundation Models

Abstract: 

Transformer-based tabular foundation models (TFMs) dominate small to medium tabular predictive benchmark tasks, yet their inference mechanisms remain largely unexplored. We present the first large-scale mechanistic study of layerwise dynamics in 6 state-of-the-art tabular in-context learning models. We explore how predictions emerge across depth, identify distinct stages of inference, and reveal latent-space dynamics that differ from those of language models. Our findings indicate substantial depthwise redundancy across multiple models, suggesting iterative refinement with overlapping computations during inference stages. Guided by these insights, we design a proof-of-concept, looped single-layer model that uses only 20% of the original model’s parameters while achieving comparable performance. The code is available at https://github.com/amirbalef/is_one_layer_enough.

---------





