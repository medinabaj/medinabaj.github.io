---
layout: publication
title: "Development and Validation of Prediction Models for Stroke and Myocardial Infarction in Type 2 Diabetes Patients Based on German Health Insurance Claims Data – Do Modern Machine Learning Methods Outperform Traditional Regression Approaches?"
date: 2024-04-11
authors: "Anna Janina Stephan, Michael Hanselmann, **Medina Bajramovic**, Simon Schosser, Michael Laxy"
journal: "Preprint"
link: "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4781312"
---
Digitalization and big health system data open new avenues for targeted prevention and treatment strategies. Despite their ubiquitarian availability, it remains unknown if health insurance claims can identify patients at high complication risk. We developed and validated prediction algorithms for stroke and myocardial infarction (MI) in patients with type 2 diabetes (T2D) based on claims and compared predictive performance of traditional regression with state-of-the-art machine and deep learning (ML/DL) methods.

Methods: We used German 2014-2019 claims with 287 predictors of 3-year MI and stroke risk. Following a train-test split approach, we applied logistic models with and without forward selection, LASSO-regularization, random forests (RF), gradient boosting (GB), multi-layer-perceptrons (MLP), and feature-tokenizer transformers (FTT). We assessed discrimination (Areas Under the Receiver-Operator and Precision-Recall Curves, AUROC and AUPRC) and calibration.

Findings: Among n=371,006 T2D patients (mean age: 67·2 years), 3·5% (n=13,030) had MIs and 3·4% (n=12,701) strokes. AUPRCs were 0·035 (MI) and 0·034 (stroke) for a null model and between 0·082 (MLP) and 0·092 (GB) for MI and between 0·061 (MLP) and 0·073 (GB) for stroke. AUROCs were 0·5 for null models, between 0·70 (RF, MLP, FTT) and 0·71 (all others) for MI and between 0·66 (MLP) and 0·69 (GB) for stroke.

Interpretation: Performance of claims-based algorithms was comparable to existing epidemiological models incorporating clinical information. ML/DL did not outperform regression-based approaches. Applying regression-based approaches may be a transparent scalable low-cost approach for cardiovascular risk stratification