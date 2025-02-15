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

**Feburary 13th 2pm CET - [Oleksander Shchur](https://shchur.github.io/)**

Title: Chronos: Time series forecasting in the age of pretrained models

Abstract: 

Time series forecasting is an essential component of decision-making in domains such as energy, retail, and finance. Traditionally, machine learning practitioners have focused on developing task-specific forecasting models that are restricted to a certain dataset or application domain. Inspired by the success of pretrained Large Language Models (LLMs) in natural language processing, it becomes imperative to explore whether a similar approach can be applied to forecasting: Can we train a single large model on huge amounts of diverse time series data, that will generalize to new unseen time series tasks? In this talk, we introduce Chronos, a family of pretrained forecasting models based on minimal modifications to LLM architectures, that accomplishes this goal. Chronos demonstrates remarkable zero-shot performance on unseen datasets, positioning pretrained models as a viable tool to greatly simplify forecasting pipelines. We discuss open challenges in the development and application of pretrained models for time series forecasting, and explore what role AutoML methods can play in overcoming them




---------

**Feburary 20th 4pm CET - [Frank Hutter](https://ml.informatik.uni-freiburg.de/profile/hutter/)**

Title: Accurate predictions on small data (and time series) with the tabular foundation model TabPFN

Abstract: 

Tabular data, spreadsheets organized in rows and columns, are ubiquitous across scientific fields, from biomedicine to particle physics to economics and climate science. The fundamental prediction task of filling in missing values of a label column based on the rest of the columns is essential for various applications as diverse as biomedical risk models, drug discovery and materials science. Although deep learning has revolutionized learning from raw data and led to numerous high-profile success stories, gradient-boosted decision trees have dominated tabular data for the past 20 years. Here we present the Tabular Prior-data Fitted Network (TabPFN), a tabular foundation model that outperforms all previous methods on datasets with up to 10,000 samples by a wide margin, using substantially less training time. In 2.8 s, TabPFN outperforms an ensemble of the strongest baselines tuned for 4 h in a classification setting. As a generative transformer-based foundation model, this model also allows fine-tuning, data generation, density estimation and learning reusable embeddings. TabPFN is a learning algorithm that is itself learned across millions of synthetic datasets, demonstrating the power of this approach for algorithm development. By improving modeling abilities across diverse fields, TabPFN has the potential to accelerate scientific discovery and enhance important decision-making in various domains. Likewise, TabPFN has enormous potential for related tabular applications such as time series or relational data. We show that TabPFN already excels at time series forecasting, outperforming foundation models built only for time series. 

---------

**Feburary 27th 3pm CET - [Thomas Nagler](https://tnagler.github.io/) and [Lennart Schneider](https://www.slds.stat.uni-muenchen.de/people/schneider/)**

Title: Reshuffling Resampling Splits Can Improve Generalization of Hyperparameter Optimization

Abstract: 

Hyperparameter optimization is crucial for obtaining peak performance of machine learning models.
The standard protocol evaluates various hyperparameter configurations using a resampling estimate of the generalization error to guide optimization and select a final hyperparameter configuration.
Without much evidence, paired resampling splits, i.e., either a fixed train-validation split or a fixed cross-validation scheme, are often recommended.
We show that, surprisingly, reshuffling the splits for every configuration often improves the final model's generalization performance on unseen data.
Our theoretical analysis explains how reshuffling affects the asymptotic behavior of the validation loss surface and provides a bound on the expected regret in the limiting regime.
This bound connects the potential benefits of reshuffling to the signal and noise characteristics of the underlying optimization problem.
We confirm our theoretical results in a controlled simulation study and demonstrate the practical usefulness of reshuffling in a large-scale, realistic hyperparameter optimization experiment.
While reshuffling leads to test performances that are competitive with using fixed splits, it drastically improves results for a single train-validation holdout protocol and can often make holdout become competitive with standard CV while being computationally cheaper.

---------

**March 27th - [Nick Erickson](https://scholar.google.com/citations?user=I0nj-TcAAAAJ&hl=en)**

Title: TBD

Abstract: TBD



