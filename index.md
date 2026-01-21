---
layout: default
---


# Taylen-Inthisane-Portfolio
Data science portfolio

# [Project 1: Diabetes Risk Prediction & Early Detection: Project Overview](https://github.com/Initial-T53/Diabetes-Risk-Project)
* Built a machine Learning model to predict diabetes diagnosis using demographic, lifestyle and metabolic indicators.
* Tested Logistic Regression, Random Forest and XGBoost ; selected Random Forest for lowest false positives.
* Used SHAP values to interpret predictions: HbA1c, fasting glucose and postprandial glucose were top predictors.
* Created a risk stratification tool with low/medium/high threasholds to guide preventive care.

![](Images/Diabetes_SHAP.png)

# [Project 2: ICU Patient Outcome Analysis : Project overview](https://github.com/Initial-T53/ICU-Patient-Analysis)
* Analyzed and worked with ICU electronic medical records to identify predictors of mortality and legnth of stay.
* Used Ordinary least squares, lasso regression, ridge regression and random forest model. GridsearchCV was used to hypertune lasso and ridge regression
* Identified features that are strong associated with patients length of stay and mortality risk
* Recommended risk-wristbands and medication recommender system.


![](Images/LOS_RF.png)

![](Images/MORT_RF.png)

# [Project 3: Amazon Sales Data Clustering : Project overview](https://github.com/Initial-T53/Amazon-Sales-Data)
* Performed customer-level feature engineering on a synthetic Amazon sales dataset, correcting inconsistent purchase amounts, product categories, and tax to enable reliable behavior analysis.
* Built two clustering pipelines: behavioral segmentation using KMeans and HDBSCAN, and attempted seasonality-aware segmentation using monthly purchasing vectors.
* Identified distinct customer personas based on spending patterns, order frequency, discount sensistivitym and basket behavior, including handling of HDBSCAN's noise cluster for unclusted customers.
* Delivered marketing-focused recommendations for each segment, highlighting opportunities for targeted promotions, churn-risk, identification, loyalty improvements and personalized customers experiences.



![](Images/Customer HDBSCAN.png)
