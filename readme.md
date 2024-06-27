# Machine Learning for Fraud Detection in E-commerce Transactions

## Overview
This project investigates the application of machine learning techniques to enhance fraud detection in e-commerce transactions. By leveraging a comprehensive dataset from Vesta, we explore feature engineering, distance prediction, and clustering analysis to identify fraudulent activities.

## Problem Statement
The increasing sophistication of financial fraud poses significant challenges to businesses and consumers. Traditional rule-based fraud detection systems often struggle to keep pace with evolving fraudulent tactics. This project aims to develop more robust and accurate fraud detection models using machine learning.

## Methodology
This project addresses three key research questions:

**RQ1: Feature Engineering and Selection**
* **Objective:** Improve fraud detection accuracy by identifying and engineering the most predictive features.
* **Techniques:** Recursive Feature Elimination (RFE), Feature Importance from Gradient Boosting, Principal Component Analysis (PCA).

**RQ2: Predicting Transaction Distances**
* **Objective:** Develop models to predict transaction distances and identify geographic anomalies indicative of fraud.
* **Techniques:** Linear Regression, XGBoost.

**RQ3: Clustering for Coordinated Fraud Detection**
* **Objective:** Utilize clustering techniques to uncover groups of transactions potentially associated with coordinated fraud.
* **Techniques:** K-Means Clustering, HDBSCAN, Hierarchical Clustering.

## Results
* **Feature Engineering:** PCA significantly enhanced model accuracy, highlighting its effectiveness in capturing relevant data structures.
* **Distance Prediction:** XGBoost models demonstrated promising results in predicting transaction distances, aiding in the identification of high-risk transactions.
* **Clustering Analysis:** K-Means Clustering provided the most interpretable and well-separated clusters, potentially revealing patterns of coordinated fraud.

## Data
* **Source:** "IEEE-CIS Fraud Detection" dataset from Kaggle, provided by Vesta.
* **Size:** Over 140,000 transactions with 434 features (transaction details, card information, addresses, Vesta-engineered features).

## Contact
Cem Kazan - kzncem@gmail.com# fraud-detection-ml
