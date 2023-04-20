---
layout: page
permalink: /schedule/
title: Schedule
description: 
nav: true
nav_order: 4
---


All seminars are happening on Thursday 4-5pm (CET), unless the description specifies a different day/time.


**April 27th - [Robert Lange](https://roberttlange.github.io/)** [(ics)](../assets/ics/automl_seminar_april_27.ics)


Title:

Discovering Black-Box Optimizers via Evolutionary Meta-Learning

Abstract:

Optimizing functions without access to gradients is the remit of black-box methods such as evolutionary optimizers. While highly general, their learning dynamics are often times heuristic and inflexible — exactly the limitations that meta-learning can address. Hence, we propose to discover effective update rules for evolution strategies and genetic algorithms via meta-learning. Concretely, our approach employs black-box optimizers parametrized by self-attention-based architectures, which guarantees the update rule is invariant to the ordering of the candidate solutions. We show that meta-evolving this system on a small set of representative low-dimensional analytic optimization problems is sufficient to discover new evolutionary optimizers capable of generalizing to unseen optimization problems, population sizes, and optimization horizons. Furthermore, the same learned optimizer can outperform established neuroevolution baselines on supervised and continuous control tasks. As additional contributions, we ablate our method's individual neural network components; reverse engineer the learned optimizer into an explicit heuristic form, which remains highly competitive; and demonstrate the positive transfer of neural network-based operators to white-box optimizers. Finally, we show that it is possible to self-referentially train an evolution strategy from scratch, using the learned update rule to drive the outer meta-learning loop. 

The corresponding paper links can be found below:
- Learned ES (ICLR 2023): https://openreview.net/forum?id=mFDU0fP3EQH
- Learned GA (GECCO 2023): https://arxiv.org/abs/2304.03995



----------


