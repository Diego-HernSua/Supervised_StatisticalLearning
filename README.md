# ⚽ Supervised Tools in Statistical Learning: FIFA23 Analysis

**Author:** Diego Hernández Suárez

---

## 📝 Description
This project involves the application of various supervised learning tools on a dataset containing statistics of players in FIFA 23. The goal was to gain insights into the best and worst players and to identify their characteristics based on their attributes. 

### Key Activities:
- **Dataset Preprocessing**: Initially, I optimized the dataset by transforming variables and changing formats to prepare it for in-depth analysis.
- **Supervised Learning Techniques**: Applied a range of classification and regression methods, such as Random Forests, Decision Trees, Logistic Regression, KNN, among others, to analyze player stats and extract meaningful insights.

---

## 📊 Dataset
The dataset includes a wide array of statistics for players featured in the EA FIFA23 video game. Some of the key attributes are:
- **Name**
- **Age**
- **Height**
- **Overall**
- **Club**
- And more...

These attributes are fundamental for conducting a precise and effective study on player performance and characteristics.

---

## 🛠️ Preprocessing
The preprocessing phase involved several techniques to refine and enhance the dataset:
- **Size Reduction**: Removed irrelevant variables to streamline the analysis.
- **Feature Engineering**: Converted variable types (e.g., from string to numerical) for better compatibility with analysis tools.
- **Data Visualization**: Employed visualization tools to gain a better understanding of the dataset and identify key patterns and trends.

---

## 🧠 Processing

### 📌 Classification Techniques:
- **LDA (Linear Discriminant Analysis)**: Used for finding the linear combinations of features that best separate classes.
- **QDA (Quadratic Discriminant Analysis)**: Like LDA but allows for quadratic decision boundaries.
- **Binary Classification (Logistic Regression)**: Applied for binary outcomes such as predicting if a player is top-tier or not.
- **Penalized Logistic Regression**: Used to handle overfitting by penalizing large coefficients.
- **Cost-sensitive Learning**: Adjusted for different costs associated with misclassifications.
- **Risk Learning**: Focused on minimizing the risk associated with predictions.
- **Decision Trees**: Utilized for both classification and regression tasks, providing interpretable models.
- **Random Forest**: An ensemble method used for improving the accuracy of predictions.
- **Gradient Boosting**: A powerful technique for improving model accuracy by combining weak learners.
- **Subsampling Techniques**: Employed to balance the dataset and improve model performance.

### 📌 Regression Techniques:
- **Linear Regression**: The basic model for predicting continuous outcomes.
- **Overfitted Linear Regression**: Explored the impact of overfitting on model performance.
- **Forward and Backward Regression**: Stepwise methods for feature selection.
- **Ridge and Lasso Regression**: Regularization techniques to prevent overfitting by penalizing large coefficients.
- **KNN (K-Nearest Neighbors)**: A non-parametric method used for both classification and regression.
- **Random Forest**: Applied here as well to handle regression tasks by averaging multiple decision trees.

---

## Required Packages
To execute the code, the following R packages are required:
```r
c("tidyverse", "plyr", "ggplot2", "MASS", "caret", "e1071", "skimr", "mice", "VIM", "glmnet", "rpart", "pROC", "class", "randomForest")

