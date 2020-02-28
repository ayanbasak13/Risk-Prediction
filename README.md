# Risk-Prediction

This repository contains the codes used for the Risk Prediction challenge organized by Analytics Vidhya. The challenge was to predict whether a customer of a financial organization is risky(likely to be a defaulter, in future, denoted by the label '1') or not risky(denoted by label '0'. The dataset used is:  train.csv. 

It is an imbalanced dataset: with 78.29% of  '0' and 21.71% of  '1'.

I have used the SMOTE algorithm to oversample the minority class. The dataset thus generated has been fitted to XGBOOST algorithm to generate the predictions.
