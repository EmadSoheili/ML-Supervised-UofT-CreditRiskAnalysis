# Credit Risk Analysis

***University of Toronto - Data Analytics Boot Camp - Module 18 - Supervised Machine Learning and Credit Risk***

---

## Overview

We are using Supervised Machine Learning to predict credit risk and distinguish good and bad loans. There are serveral input variables and one binary output variable which is "loan_status" with possible outcomes of "low_risk" and "high_risk".
Logically, there are many more low risk applicants than the high risk ones. Therefore, the dataset is imbalanced and we should tackle this issue with a proper solution. Here in this project, we are using the resampling method to balance the datasets. We are also using two classification model to cop with bias.
We will create six different models with the following approaches.
  * Using resampling
    1. Naive Random oversampling
    2. SMOTE oversampling
    3. Cluster Centriod undersamling
    4. SMOTEENN (Combination of oversampling and undersamling)
  * Using Classification models which can reduce bias.
    5. BalancedRandomForestClassifier model
    6. EasyEnsembleClassifier model
    
---

## Result

For all 6 models, we have executed different evaluation methods including Accuracy score, Confusion Matrix, and Classification Report.
The result of evaluation will be something like the following image.

![](Images/evaluation.png)
