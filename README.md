# Supervised Tools in Statistical Learning: FIFA23 Analysis
**Author:** Diego Hernández Suárez

## Description
In this project I worked with a data set related to the stats of all the players in FIFA23, where I applied different classification and regression with different supervised learning techniques in order to obtain insights of the best and worst players and how to identify their characteristics depending on its attributes. During the project, I firstly pre processed the data set in order to transform variables and change its format in order to make it more optimal to work with it. Furthermore, I employed a several amount of tools such as random forests, decision trees, logistic regressions, KNN, among others in order to analyze and understand the data.

## Data set
This data set consists on the different statistics of the players that are in the videogame EA FIFA23, some of these variables could be the Name, Age, Height, Overall, Club, etc... With all these attributes are crucial in order to develop a precise and effective study.

## Preprocessing
I employed different solutions in order to obtain a better data set, such as reducing the data set by deleting some non-relevant variables, changing some variables types (for instance, from str to numerical) by performing featuring engineering or by employing visualization tools in order to understand the relevant aspects.

## Processing
#### Classification
- LDA
- QDA
- Binary classification (LogisticR)
- Penalized LR
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
- Ridge and Lasso 
- KNN
- Random Forest

## Packages required
In order to execute the code, it is necessary to load the following R packages:
```r
c("tidyverse", "plyr", "ggplot2", "MASS", "caret", "e1071", "skimr", "mice", "VIM", "glmnet", "rpart", "pROC", "class", "randomForest")
```
