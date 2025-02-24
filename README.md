# Telco Churn Classification Project

## Description
This project analyses data about a fictional telco company that provides landline phone and Internet services to 7043 users in California. Multiple demographics are included for each customer, and it indicates which customer churned and which customer stayed. The goal of this project is to find a model that will predict as accurately as possible if a customer will churn or not.

## Data Source
The original data comes from the [IBM Telco Customer Churn Blog](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113).

## Libraries Used
* matplotlib
* numpy
* pandas
* seaborn
* sklearn

## Exploratory Data Analysis (EDA)
The following questions are answered in this project:
* What is the overall count of churn value?
* What is the percentage of male vs. female by churn value?
* What is the churn value count by contract type?
* Is there a relationship between churn value and monthly charges?
* What's the most popular payment method?
* Do more people enroll in device protection?
* What is the percentage of people who go paperless?
* What are the top 5 reasons why customers churn?
* What is the most correlated factor to churn value?

## Data Modeling Results and Evaluation
Three different classification models were explored to predict the Churn Value: 
* Logistic Regression
* K-Nearest Neighbors
* Suport Vector Machines

The best performing model was the Logistic Regression, with an accuracy score of 90%. It also has an 81% precision, 80% recall and 81% f1-score for predicting the Churn Value.