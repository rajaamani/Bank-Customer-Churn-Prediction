# Bank Customer Churn Prediction

![Bank Customer Churn Prediction](https://github.com/rajaamani/Credit-Card-Fraud-Detection-using-Autoencoders/assets/101103515/23d8bf42-c03a-4e05-b504-b658b16ad0a7)

## Table of Contents
1. [Summary](#summary)
2. [Introduction](#introduction)
3. [Data](#data)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Data Transformation](#data-transformation)
6. [Model Building](#model-building)
7. [Conclusion](#conclusion)

## Summary <a name="summary"></a>
Customer churn, also known as customer attrition, refers to customers discontinuing their relationship with a business or organization. In the banking industry, predicting customer churn is of great importance as it allows banks to address customer needs, improve retention strategies, and save costs associated with acquiring new customers. Identifying at-risk customers allows banks to implement personalized retention strategies, improving customer experience and reducing attrition rates. This project aims to perform exploratory data analysis (EDA) and develop a churn prediction model to forecast which customers are likely to churn based on historical data and various features.

## Introduction <a name="introduction"></a>
In the banking industry, retaining customers is crucial for long-term success. Customer churn can result in revenue loss and increased customer acquisition costs. Predicting which customers are likely to churn and implementing proactive retention strategies is essential for reducing churn rates.

This project utilizes a dataset of bank customer information, including demographic data, account balances, and product usage. We start by exploring the data to understand its characteristics and distribution. We then preprocess the data by handling missing values, encoding categorical variables, and normalizing numerical features. Next, we build a churn prediction model using machine learning algorithms.

## Data <a name="data"></a>
The dataset used in this project is a fictional bank customer dataset and contains the following columns:
- CustomerId: Unique identifier for each customer
- Surname: Customer's last name
- CreditScore: Credit score of the customer
- Geography: Country of the customer (e.g., France, Germany, Spain)
- Gender: Gender of the customer (e.g., Male, Female)
- Age: Age of the customer
- Tenure: Number of years the customer has been with the bank
- Balance: Account balance of the customer
- NumOfProducts: Number of bank products used by the customer
- HasCrCard: Whether the customer has a credit card (1 for yes, 0 for no)
- IsActiveMember: Whether the customer is an active member (1 for yes, 0 for no)
- EstimatedSalary: Estimated annual salary of the customer
- Exited: Whether the customer churned (1 for yes, 0 for no)

## Exploratory Data Analysis <a name="exploratory-data-analysis"></a>
- Categorical Variables: We analyze categorical variables like Geography, Gender, and IsActiveMember to understand their distribution and their impact on customer churn.
- Numerical Variables: We examine numerical variables like CreditScore, Age, Tenure, Balance, NumOfProducts, and EstimatedSalary, visualizing their distributions and identifying patterns related to churn.

## Data Transformation <a name="data-transformation"></a>
- We drop irrelevant columns (CustomerId, Surname) that do not contribute to the churn prediction.
- We perform one-hot encoding on categorical variables (Geography, Gender) to convert them into numerical representations.
- We normalize numerical features to bring them into a consistent scale for modeling.

## Model Building <a name="model-building"></a>
- We build a churn prediction model using various machine learning algorithms, including Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, Naive Bayes, and XGBoost.
- We evaluate model performance using cross-validation and select the best-performing model.
- We use the selected model to make predictions on the testing data and evaluate its accuracy, precision, recall, and confusion matrix.

## Conclusion <a name="conclusion"></a>
- Balancing the dataset using the Synthetic Minority Over-sampling Technique (SMOTE) has significantly improved the accuracy of churn prediction.
- Recommendations for reducing churn rates and boosting customer retention include personalized engagement, targeting specific demographics, enhancing product offerings, and continuous monitoring and evaluation of retention strategies.

This project provides valuable insights and a predictive model to help banks proactively reduce customer churn and improve overall customer satisfaction.

