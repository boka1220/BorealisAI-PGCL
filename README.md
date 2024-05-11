# Overview
This repository contains the code and data analysis for our project on predicting post-liver transplant mortality, developed by the PGCL Roomies team under the guidance of our mentors Hossein Sharifi and Lauren Howcroft. Our project focuses on enhancing the prediction of post-transplant mortality and aiding the MELD score to improve patient outcomes and liver transplant prioritization.

# Project Description
Liver transplantation is a critical intervention for patients with severe liver conditions such as acute liver failure, hepatocellular carcinoma (HCC), and cirrhosis. However, post-transplant mortality remains a significant challenge. This project aims to develop a model that can predict post-transplant mortality to better manage those at higher risk by addressing risk factors before and after surgery.

# Dataset
The dataset utilized in this project comes from the United Network for Organ Sharing (UNOS) - SRTR (Scientific Registry of Transplant Recipients) Database, which includes data from every transplant and organ donation that has occurred in the US since October 1, 1987.

# Total patients: Over 300,000
Datasets combined: Waiting List History, Liver Data, Follow-Up Data

# Methodology
Our approach involves:

1. Defining the binary outcome as:
1: Graft failure before 180 days
0: Survival until 180 days
2. Using oversampling (SMOTE) to balance the dataset.
3. Employing various machine learning models, initially using only pre-transplant data and later including post-transplant data for improved results.
Models Used
Neural Network
Logistic Regression
XGBoost
Decision Tree
Random Forest
4. Results
Our best-performing model achieved an ROC AUC of 0.836 and an F1 score of 0.506, indicating a strong capability in predicting graft failure.
