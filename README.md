# Risk-Prediction

This repository contains the codes used for the Risk Prediction challenge organized by Analytics Vidhya. The challenge was to predict whether a customer of a financial organization is risky(likely to be a defaulter, in future, denoted by the label '1') or not risky(denoted by label '0'. 

It is an imbalanced dataset: with 78.29% of  '0' and 21.71% of  '1'. I have used the SMOTE algorithm to oversample the minority class. The final dataset used is:  https://github.com/ayanbasak13/Risk-Prediction/blob/master/train.csv. 

The dataset thus generated has been fitted to XGBOOST(https://github.com/ayanbasak13/Risk-Prediction/blob/master/XG_Boost.ipynb), CATBOOST(https://github.com/ayanbasak13/Risk-Prediction/blob/master/RiskPred.ipynb) and Logistic Regression with Recursive Feature Elimination(RFE) (https://github.com/ayanbasak13/Risk-Prediction/blob/master/Logistic_Imbalance(SMOTEENN)-RFE.ipynb) algorithms to generate the predictions. The XGBOOST model had the best performance on the private test test for the competition and was used for final predictions.
