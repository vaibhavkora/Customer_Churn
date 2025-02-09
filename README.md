
# Customer Churn

This repository contains a Jupyter Notebook that analyzes customer churn using data science and machine learning techniques. The goal is to identify key factors leading to customer churn and build predictive models to minimize attrition.

![Image_Alt](cus.jpg)



## Project Overview

This project aims to predict customer churn using a dataset containing demographic, subscription, and usage details. The analysis includes exploratory data analysis (EDA), feature engineering, and machine learning model implementation.

## Dataset

The dataset includes:
- **Demographics**: Gender, senior citizen status.
- **Subscription Details**: Contract type, internet service, payment method.
- **Billing & Usage**: Monthly charges, total charges.
- **Churn Label**: Indicates whether a customer left or stayed.
## Key Features

Data Preprocessing: Handling missing values, selecting relevant features.
Exploratory Data Analysis (EDA): Visualization of customer behavior, churn trends, and key influencing factors.
Feature Engineering: Creating new features to improve model accuracy.
Machine Learning Models: Implementing various classification models such as:
Logistic Regression
Decision Trees
Random Forest
Model Evaluation: Using accuracy, precision, recall, F1-score, confusion matrix.


## Steps Performed in the Notebook

 1. **Data Preprocessing** 
 - Handling missing values and feature encoding.
2. **Exploratory Data Analysis (EDA)** 
- Visualizing key   trends.
3. **Feature Engineering** 
 - Creating meaningful features.
4. **Model Training** 
- Implementing classification models (Logistic Regression, Random Forest, etc.).
5. **Model Evaluation** 
- Using accuracy, precision, recall, F1-score.
## Installation

Install my-project with npm

```
1. Clone this repository:
   ```
   git clone : https://github.com/vaibhavkora/customer-churn.git

pip install pandas numpy matplotlib seaborn scikit-learn

jupyter notebook Customer_churn.ipynb


    
## Key Insights
- Customers with month-to-month contracts are more likely to churn.
- Electronic check payments are associated with higher churn rates.
- Higher tenure and lower monthly charges reduce churn probability.
- The best-performing model achieved an accuracy of 85%.
