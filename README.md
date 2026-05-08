# Heart Attack Risk Factor Analysis – Indonesia Dataset

## Description
Statistical and machine learning analysis of clinical and demographic 
risk factors associated with heart attacks, using a publicly available 
Indonesian dataset sourced from Kaggle (158,355 observations, 28 variables).

## Authors
Samuel Amuzu, Nick Schaufelberger, Julian Purtschert

## Models Applied
- Linear Regression (LM) — fasting blood sugar prediction
- Logistic Regression (GLM Binomial) — heart attack classification
- Generalised Additive Model (GAM) — non-linear risk effects
- Poisson Regression (GLM) — risk factor count modelling
- Support Vector Machine (SVM) — best performing classifier (AUC: 0.79)
- Neural Network — feed-forward classifier

## Key Findings
- Strongest risk factors: previous heart disease (OR: 5.4), 
  hypertension (OR: 4.7), diabetes (OR: 3.5)
- SVM achieved best predictive performance (72% accuracy, AUC: 0.79)
- Neural network failed to outperform the baseline classifier
- GAM revealed non-linear effects of age and fasting blood sugar

## Requirements
R with the following packages:
tidyverse, ggplot2, caret, e1071, pROC, mgcv, neuralnet, corrplot

## Usage
Open and run the R script/RMarkdown file sequentially.
Set the correct file path for the dataset on your machine.
