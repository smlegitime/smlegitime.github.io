---
title: "Improving Opioid Use Disorder Risk Modelling through Behavioral and Genetic Feature Integration" 
date: 2023-08-01
tags: ["Bioinformatics","machine learning","opioid use","risk prediction"]
author: ["Sybille Légitime","Kaustubh Prabhu","Devin McConnell","Bing Wang", "Dipak K. Dey","Derek Aguiar"]
description: "The study presents a new framework that combines genetic data and behavioral mobility patterns to improve opioid use disorder (OUD) risk prediction, finding that integrating these features enhances risk modeling accuracy and may support more personalized clinical decisions, though further evaluation is needed before clinical use." 
summary: "The study presents a new framework that combines genetic data and behavioral mobility patterns to improve opioid use disorder (OUD) risk prediction, finding that integrating these features enhances risk modeling accuracy and may support more personalized clinical decisions, though further evaluation is needed before clinical use."
# cover:
#     image: "paper2.png"
#     alt: "Dimensions of a sausage dog"
#     relative: true
editPost:
    URL: "https://arxiv.org/abs/2309.10837"
    Text: "Preprint"

---

---

##### Download

+ [Code and data](https://github.com/bayesomicslab/OUD-Risk-Prediction)

---

##### Abstract

Opioids are an effective analgesic for acute and chronic pain, but also carry a considerable risk of addiction leading to millions of opioid use disorder (OUD) cases and tens of thousands of premature deaths in the United States yearly. Estimating OUD risk prior to prescription could improve the efficacy of treatment regimens, monitoring programs, and intervention strategies, but risk estimation is typically based on self-reported data or questionnaires. We develop an experimental design and computational methods that combine genetic variants associated with OUD with behavioral features extracted from GPS and Wi-Fi spatiotemporal coordinates to assess OUD risk. Since both OUD mobility and genetic data do not exist for the same cohort, we develop algorithms to (1) generate mobility features from empirical distributions and (2) synthesize mobility and genetic samples assuming an expected level of disease co-occurrence. We show that integrating genetic and mobility modalities improves risk modelling using classification accuracy, area under the precision-recall and receiver operator characteristic curves, and F1 score. Interpreting the fitted models suggests that mobility features have more influence on OUD risk, although the genetic contribution was significant, particularly in linear models. While there exist concerns with respect to privacy, security, bias, and generalizability that must be evaluated in clinical trials before being implemented in practice, our framework provides preliminary evidence that behavioral and genetic features may improve OUD risk estimation to assist with personalized clinical decision-making.

---

<!-- ##### Figure 2: Dimensions of a sausage dog

![](paper2.png)

---

##### Citation

Prinzel, Florianus, and Moritz-Maria von Igelfeld. 2004. "The Finer Points of Sausage Dogs." *Journal of Canine Science* 43 (2): 89–109. http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs.

```BibTeX
@article{PI04,
author = {Florianus Prinzel and Moritz-Maria von Igelfeld},
year = {2004},
title ={The Finer Points of Sausage Dogs},
journal = {Journal of Canine Science},
volume = {43},
number = {2},
pages = {89--109},
url = {http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs}}
```

---

##### Related material

+ [Presentation slides](presentation2.pdf)
+ [Wikipedia entry](https://en.wikipedia.org/wiki/The_Finer_Points_of_Sausage_Dogs) -->
