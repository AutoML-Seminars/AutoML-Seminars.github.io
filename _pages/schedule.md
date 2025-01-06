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

**January 9th 3pm - [Julien Siems](https://scholar.google.de/citations?user=rKgTTh8AAAAJ&hl=de) and [Riccardo Grazzi](https://scholar.google.de/citations?user=9Tlyx1IAAAAJ&hl=de)**

Title: Unlocking State-Tracking in Linear RNNs Through Negative Eigenvalues

Abstract: 

Linear Recurrent Neural Networks (LRNNs) such as Mamba, RWKV, GLA, mLSTM, and DeltaNet have emerged as efficient alternatives to Transformers in large language modeling, offering linear scaling with sequence length and improved training efficiency. However, LRNNs struggle to perform state-tracking which may impair performance in tasks such as code evaluation or tracking a chess game. Even parity, the simplest state-tracking task, which non-linear RNNs like LSTM handle effectively, cannot be solved by current LRNNs. Recently, Sarrof et al. (2024) demonstrated that the failure of LRNNs like Mamba to solve parity stems from restricting the value range of their diagonal state-transition matrices to [0,1] and that incorporating negative values can resolve this issue. We extend this result to non-diagonal LRNNs, which have recently shown promise in models such as DeltaNet. We prove that finite precision LRNNs with state-transition matrices having only positive eigenvalues cannot solve parity, while complex eigenvalues are needed to count modulo 3. Notably, we also prove that LRNNs can learn any regular language when their state-transition matrices are products of identity minus vector outer product matrices, each with eigenvalues in the range [−1,1]. Our empirical results confirm that extending the eigenvalue range of models like Mamba and DeltaNet to include negative values not only enables them to solve parity but consistently improves their performance on state-tracking tasks. Furthermore, pre-training LRNNs with an extended eigenvalue range for language modeling achieves comparable performance and stability while showing promise on code and math data. Our work enhances the expressivity of modern LRNNs, broadening their applicability without changing the cost of training or inference.



---------

**January 16th - [Katie Everett](https://www.katieeverett.com/)**

Title: TBD

Abstract: TBD
