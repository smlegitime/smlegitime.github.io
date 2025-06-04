---
title: "Improving Opioid Use Disorder Risk Modelling through Behavioral and Genetic Feature Integration" 
date: 2023-08-01
tags: ["Bioinformatics","machine learning","opioid use","risk prediction"]
author: ["Sybille Légitime","Kaustubh Prabhu","Devin McConnell","Bing Wang", "Dipak K. Dey","Derek Aguiar"]
description: "The study presents a new framework that combines genetic data and behavioral mobility patterns to improve opioid use disorder (OUD) risk prediction, finding that integrating these features enhances risk modeling accuracy and may support more personalized clinical decisions, though further evaluation is needed before clinical use."
summary: "The study presents a new framework that combines genetic data and behavioral mobility patterns to improve opioid use disorder (OUD) risk prediction, finding that integrating these features enhances risk modeling accuracy and may support more personalized clinical decisions, though further evaluation is needed before clinical use."
editPost:
    URL: "https://arxiv.org/abs/2309.10837"
    Text: "Preprint"
showToc: true
disableAnchoredHeadings: false

---

## Abstract

Opioids are an effective analgesic for acute and chronic pain, but also carry a considerable risk of addiction leading to millions of opioid use disorder (OUD) cases and tens of thousands of premature deaths in the United States yearly. Estimating OUD risk prior to prescription could improve the efficacy of treatment regimens, monitoring programs, and intervention strategies, but risk estimation is typically based on self-reported data or questionnaires. We develop an experimental design and computational methods that combine genetic variants associated with OUD with behavioral features extracted from GPS and Wi-Fi spatiotemporal coordinates to assess OUD risk. Since both OUD mobility and genetic data do not exist for the same cohort, we develop algorithms to (1) generate mobility features from empirical distributions and (2) synthesize mobility and genetic samples assuming an expected level of disease co-occurrence. We show that integrating genetic and mobility modalities improves risk modelling using classification accuracy, area under the precision-recall and receiver operator characteristic curves, and F1 score. Interpreting the fitted models suggests that mobility features have more influence on OUD risk, although the genetic contribution was significant, particularly in linear models. While there exist concerns with respect to privacy, security, bias, and generalizability that must be evaluated in clinical trials before being implemented in practice, our framework provides preliminary evidence that behavioral and genetic features may improve OUD risk estimation to assist with personalized clinical decision-making.

---

## View repository

+ Model repository: [GitHub link](https://github.com/bayesomicslab/OUD-Risk-Prediction)
