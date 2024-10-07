# credit_card_fraud_detection

## Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions. By leveraging a dataset of transactions, the model can differentiate between fraudulent and non-fraudulent activity, helping to prevent potential fraud. 

The dataset is highly imbalanced, as fraudulent transactions are rare compared to legitimate ones. Techniques like data preprocessing, feature engineering, and resampling methods are applied to handle this imbalance and improve model performance.

## Dataset
The dataset used for this project contains transactions made by European cardholders over two days in September 2013. It consists of 284,807 transactions, where 492 are fraudulent. The dataset is publicly available and can be found [here](https://www.kaggle.com/mlg-ulb/creditcardfraud).

- **Features:** The features are anonymized and represented as numerical values obtained through a PCA transformation. There are 30 features, including `Time`, `Amount`, and `Class` (target variable, 1 for fraud, 0 for legitimate).
- **Imbalanced Dataset:** Special care was taken to address the imbalance in the dataset (492 fraudulent transactions out of 284,807).

## Installation and setup
To run this project locally, you need to have Python installed.

## Clone this repositary
git clone https://github.com/HarshGosula/credit-card-fraud-detection.git

