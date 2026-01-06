# Machine Learning Approaches Fantasy Football Player Evaluation

## Description
This project applies multiple machine learning models to predict Points-Per-Reception (PPR) fantasy football points using historical NFL player statistics. The goal is to compare linear, regularized, nonparametric, and ensemble methods for player performance evaluation.

## Models
- Multiple Linear Regression  
- Ridge Regression (L2)  
- Lasso Regression (L1)  
- Random Forest Regression  
- k-Nearest Neighbors (kNN)

## Data
- Source: Kaggle – Fantasy Football Data (2017–2023)  
- Observations: 3,388 player-season records  
- Positions: QB, RB, WR, TE  
- Target variable: `FantasyPoints` (PPR scoring)

## Tools
- R  
- tidyverse  
- caret  
- glmnet  
- randomForest  
- FNN  

## Workflow
1. Merge player statistics with Average Draft Position (ADP) data.
2. Clean and preprocess numeric predictors.
3. Perform exploratory data analysis (EDA).
4. Train and evaluate models using train/test splits.
5. Compare performance using RMSE and R².

## Author
Elizabeth Thompson
