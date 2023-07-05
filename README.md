# Loan-Risk-Classification-With-Python
A P2P Lending Application Company gave a task to a data scientist to make a machine learning model to classify whether a borrower is a high-risk or low-risk borrower. 

## Dataset Overview
A little **summary** of this dataset: 
- Based on the application type, this is a loan for individual data.
- There are 75 features originally.
- 17 empty features (100% null value).
- 17 Target Leakage.
- Target comes from the loan status feature.
- 20 features with null values (exclude the 100% empty).
- No duplicated rows based on member_id.
- 21 numerical features (exclude index, id, and member id).
- 17 categorical features.

## Exploratory Data Analysis
1. Statistic Descriptive
2. Univariate Analysis
3. Bivariate Analysis
4. Multivariate Analysis

## Preprocessing
1. Drop unnecessary columns
2. Handle missing values
3. Feature engineering
4. Feature transformations
5. Feature selection

## Modelling
1. Train test split
2. Scaling data
3. Machine learning algorithm
4. Feature importance

## Result
- Models: Logistic regression
- F1 Score: 0.87-0.88
- ROC: 0.68
- Feature importance: Revolving utilization rate and annual income

The results are not the best yet and there are still a lot of improvements that can be done by redefining the right target, adding preprocessing methods like the weight of evidence and information value, or using another machine learning algorithm. 


