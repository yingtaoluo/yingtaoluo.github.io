---
title: "Benchmarking Waitlist Mortality in Heart Transplantation Through Time-to-Event Modeling using New Longitudinal UNOS Dataset"
collection: talks
type: "Oral Presentation"
permalink: /talks/talk-2
venue: "World Transplant Congress 2025"
date: 2025-08-03
location: "San Francisco, CA, USA"
---

![image](https://github.com/user-attachments/assets/81ce7739-1434-42cf-b4f2-0528779ca53b)


Purpose: This study develops and benchmarks interpretable machine learning models for transplant mortality prediction for decision making when a donor heart becomes available, with the aim of supporting clinicians in optimizing patient outcomes using real-time, data-driven insights.

Methods: We utilize a new and comprehensive dataset of donors, recipients, and organs from the United Network for Organ Sharing (UNOS), comprising 25,610 records and 247 variables after data processing and feature engineering. Several machine learning models, including logistic regression, random forest, XGBoost, multilayer perceptron, and transformer-based models, were trained and evaluated on the task, respectively, of one-year, three-year and five-year mortality prediction. We conducted extensive hyperparameter tuning and cross-validation, assessing model performance using standard classification metrics, with a primary focus on the C-statistic (AUC). Feature importance was analyzed using SHAP values and logistic summary to ensure clinical interpretability.

Results: Our best-performing model, XGBoost, achieved an AUC of 0.93, significantly outperforming previous benchmarks in the literature (AUC range: 0.56–0.84). The inclusion of additional patient, donor, and organ variables substantially improved predictive performance. Critical predictors included patient information such as serum total bilirubin, dialysis, creatinine clearance, total waitlist days, body mass index, cardiac index, on ventilators, etc., and some donor and organ variables. The model’s high interpretability, validated through logistic regression and SHAP analysis, provides actionable insights for clinical decision-making.

Conclusions: This study demonstrates that machine learning models can provide highly accurate and interpretable predictions of post-transplant mortality with well-tuned feature engineering and model selection. These findings have significant implications for enhancing patient survival, improving donor heart allocation decisions and reducing organ wastage. Future work will focus on validating the results further with new data and integrating these models into real-time clinical decision support systems.
