---
title: "Bayesian Networks and Machine Learning for COVID-19 Severity Explanation"
excerpt: "We presented a three-stage data-driven approach to distill the hidden information about COVID-19. The first stage employs a Bayesian network structure learning method to identify the causal relationships among COVID-19 symptoms and their intrinsic demographic variables. As a second stage, the output from the Bayesian network structure learning, serves as a useful guide to train an unsupervised machine learning (ML) algorithm that uncovers the similarities in patients' symptoms through clustering. The final stage then leverages the labels obtained from clustering to train a demographic symptom identification model which predicts a patient's symptom class and the corresponding demographic probability distribution.
<br/><br/>
<img src='/images/BN_ML Covid Framework.jpg' width='500' height='150'>"
collection: portfolio
---

The COVID-19 global pandemic spurred many researchers to explore various methods to predict, forecast and analyze the impact of the COVID-19 virus. Just as anyone would imagine, we opine that it is possible that if the society has an understanding about the COVID-19 disease, its symptoms, how it spreads, and the degree of its severity across different demographics, they can better plan their lives and become resilient to the threat it poses. However, such public awareness relies on availability and access to historical data, and knowledge about the disease. 

Our work addressed the information and knowledge awareness limitation about the COVID-19 disease by: 
1. Developing a probabilistic graphical model from COVID-19 dataset, where the nodes represent symptoms (i.e., variables or features), and the edges represent the causal relationship between them. The idea is that, since there are several symptoms collected for patients’ cases, it is intuitive to study the (in)dependence mapping between these features;
2. Developing an unsupervised machine learning (ML) algorithm that learns (and extracts) the similarities between the patients' symptoms and groups them into appropriate classes (or clusters). The task of the ML algorithm is unsupervised as it requires no human intervention on labeling the patients’ cases according to some prior knowledge. The idea is to learn unknown patterns in patients' symptoms which might reflect their demographics; and
3. Developing a supervised learning algorithm which can accurately predict a patient's demographic symptom class (i.e., age and gender) given the patient's COVID-19 symptoms as input.

[Read full paper.](https://arxiv.org/abs/2406.10807)
