# Blood Pressure Analysis and Prediction
## Josh McComack
## Overview
In this Jupyter Notebook I investigate the feasibility of predicting systolic and diastolic blood pressure based on the [National Health and Nutrition Examination Survey](https://www.kaggle.com/cdc/national-health-and-nutrition-examination-survey/home) (NHANES) data set from 2013-2014 found on kaggle.com. The primary questions I wish to answer are:
1. Which variables from the survey are most predictive empirically and do they correspond to the what mainstream literature identifies as key factors in blood pressure levels?
2. Comparing scikit-learn’s SGDRegressor, MultiTaskLasso, and RandomForestRegressor, which regression model offers the best predictions on this data set?
3. Does the best model perform well enough to serve as a possible supplementary or alternative way of “measuring” blood pressure?

## Install
[download](https://www.anaconda.com/download/) and install the Anaconda package manager.

## Launch
Open a terminal in the root directory of this project and enter:
```
jupyter notebook
```