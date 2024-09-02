# Supervised Tools in Statistical Learning: FIFA23 Analysis
Application of Supervised Learning Tools using a data set containing the stats of the different players in FIFA 23.
**Author:** Diego Hernández Suárez

## Description
In this project, I worked with a dataset related to the stats of all players in FIFA23. I applied various classification and regression techniques using supervised learning to gain insights into the best and worst players and how to identify their characteristics based on their attributes. Initially, I preprocessed the dataset by transforming variables and changing formats to optimize it for analysis. Additionally, I employed several tools such as random forests, decision trees, logistic regression, KNN, among others, to analyze and understand the data.

## Dataset
This dataset consists of various statistics of the players in the EA FIFA23 video game. Some of these variables include Name, Age, Height, Overall, Club, etc. These attributes are crucial for developing a precise and effective study.

## Preprocessing
I applied different techniques to enhance the dataset, such as reducing its size by removing irrelevant variables, changing variable types (e.g., from string to numerical) through feature engineering, and using visualization tools to understand relevant aspects.

## Processing
#### Classification
- LDA (Linear Discriminant Analysis)
- QDA (Quadratic Discriminant Analysis)
- Binary classification (Logistic Regression)
- Penalized Logistic Regression
- Cost-sensitive learning
- Risk learning
- Decision Trees
- Random Forest
- Gradient Boosting
- Subsampling Techniques

#### Regression
- Linear Regression
- Overfitted Linear Regression
- Forward and Backward Regression
- Ridge and Lasso Regression
- KNN (K-Nearest Neighbors)
- Random Forest

## Required Packages
To execute the code, the following R packages are required:
```r
c("tidyverse", "plyr", "ggplot2", "MASS", "caret", "e1071", "skimr", "mice", "VIM", "glmnet", "rpart", "pROC", "class", "randomForest")

