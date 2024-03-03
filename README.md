# **Dataset Introduction**

This repository contains the analysis of an advertising dataset, which includes metrics from online advertising campaigns. The primary focus is to compute and analyze the Return on Advertising Spend (ROAS) to gain insights into the efficiency of ad campaigns and identify factors that can enhance their performance.

# **Objective**

The main goal is to predict ROAS and understand its determinants. This involves data preprocessing, feature engineering, model training and selection, and evaluation of model performance with a test dataset.

**Methodology**
Data is first loaded and examined to understand its structure and contents.
Variable names are abbreviated for easier handling during analysis.
Feature engineering is performed to calculate new metrics such as Click-Through-Rate (CTR), Cost Per Click (CPC), and others, which are necessary for the computation of ROAS.
Data is partitioned into training and test sets to ensure a fair evaluation of the models.
Various regression models are trained, including simple linear regression, stepwise regression, Principal Component Regression (PCR), and Partial Least Squares (PLS).
Models are evaluated using cross-validation on the training data and Root Mean Squared Error (RMSE) on the test data.

# **Packages**
visdat, DataExplorer for data exploration.
tidyverse for data manipulation and visualization.
caret for the machine learning workflow.
recipes for feature engineering.
forecast for time series forecasting.

# **Results**

The analysis includes the training of different models and the evaluation of their performance. Variable importance is also assessed to understand the most significant predictors of ROAS.
