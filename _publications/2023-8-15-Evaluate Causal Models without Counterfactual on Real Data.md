---
title: "Evaluate Causal Models without Counterfactual on Real Data"
collection: publications
category: Rejected Papers
permalink: /publication/2023-9-25-Evaluate Causal Models without Counterfactual on Real Data
excerpt: 'Problem: Evaluation of individual treatment effect prediction. Solution: Independently, identically, distributed error assumption.'
date: 2023-8-15
venue: 'Rejected by 2023 AAAI'
paperurl: '/files/Evaluate Causal Models without Counterfactual on Real Data.pdf'
---

The evaluation of individual treatment effect (ITE) prediction is the most critical challenge for causal learning. The key issue is that only one potential outcome can be measured for an individual in reality, even for test data in randomized trials, since one cannot be treated and untreated simultaneously. The evaluation of existing ITE models mainly relies on synthetic outcomes and nearest neighbor matching. However, synthetic outcomes cannot be generalized to the real world well, and the evaluation of matched individuals is also not trivial. Therefore, it is desired that an evaluation scheme can directly judge which learned ITE model has a more accurate prediction for both individuals and population. In this paper, we propose comparing the ITE prediction error of different models on real data for both individuals and population. The ITE model input is pretreatment and treatment, and with the outcome as the model output, ITE can be calculated by difference. The outcome prediction error with the same treatment for factual and counterfactual individuals is independently distributed on the test dataset. To infer the distribution from factual data, we also assume that the factual indicators are independent of potential errors, which can be regarded as satisfied when the treatment is a simple randomization. Therefore, two models with given predicted potential outcomes and factual dataset can be evaluated by the confidence level that ITE prediction (mean) square error of one model is smaller than or equal to the other model for both individuals and population. Experimental studies show the effectiveness of the proposed evaluation scheme, and comparisons on a real dataset ALERT also show improving the model’s performance in individuallevel is more difficult than in population-level.

[Paper](/files/Evaluate Causal Models without Counterfactual on Real Data.pdf)