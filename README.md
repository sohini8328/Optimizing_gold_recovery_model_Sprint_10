# Optimizing_gold_recovery_model_Sprint_10

Gold Recovery Estimation Project

Introduction
The primary objective of this project is to ensure the accuracy of the raw data stored in the warehouse database. This involves meticulous data validation and correction processes. Ultimately, the goal is to develop a machine learning model capable of estimating the amount of gold recovery from the ore extracted by the mining company. By leveraging cleaned and validated data, this model aims to provide reliable predictions, optimize mining operations, and maximize gold recovery.

Conclusion
Key Findings
- Data Validation & Cleaning:- The mean absolute error (MAE) for the training set was approximately 9.30, indicating close alignment between the warehouse database and actual values.
- Concentration trends across purification stages:- Gold (Au): Levels consistently increased.
- Silver (Ag): Levels decreased.
- Lead (Pb): Levels remained relatively constant.

- Anomalies in the 0-20 range were excluded to maintain model accuracy.

- Data Distribution:- The feed distribution in the training and test sets was similar, with most data ranging between 6-8 cubic meters, confirming no signs of overfitting or underfitting.

- Model Evaluation:- Linear Regression:- Emerged as the most robust model with a SMAPE of 10.66, outperforming other evaluated models.
- Demonstrated consistent performance across cross-validation and test sets.

- Decision Tree Regressor:- Displayed less reliable results.

- Despite its promise, the machine learning model's performance (SMAPE: 9.044) was not significantly better than the constant model (SMAPE: 7.62).

Recommendation
While the machine learning model showed potential, its improvement over the constant model was minimal. The Linear Regression model remains a strong candidate for accurately estimating gold recovery, but further enhancements in feature engineering or algorithm selection could bridge the gap for greater predictive power.



