# Data Science End of P3 Project

# Telecom Customer Churn Prediction

# Overview

Customer churn is a major challenge in the telecommunications industry because losing an existing customer directly reduces recurring revenue and acquiring new customers is significantly more expensive than retaining current ones. This project develops a machine learning classification model capable of predicting whether a customer is likely to discontinue telecom services.

The goal is to enable proactive intervention — allowing the company to identify at-risk customers early and implement retention strategies before cancellation occurs.

This project follows the full workflow including business understanding, data preparation, predictive modeling, evaluation, and actionable recommendations.

# Business and Data Understanding
Stakeholder
The primary stakeholders are the telecom company’s:
- Customer Retention Team
- Marketing Department
- Revenue Planning Team

These teams need a system that highlights customers at high risk of leaving so targeted retention actions can be taken efficiently.

# Business Problem

Customer churn results in revenue loss and unstable growth. The company currently reacts only after customers cancel services. The business requires a predictive system that identifies customers likely to churn so preventative actions can be applied in advance.

# Dataset

The dataset contains telecom customer account information including:
- Service subscriptions
- Contract type
- Monthly charges
- Tenure
- Support services
- Usage behavior

The target variable indicates whether a customer churned (Yes/No), making this a binary classification problem.

This dataset was chosen because it reflects real operational customer behavior and supports predictive retention decision-making.

# Modeling

Multiple classification models were developed and compared to identify the best predictive solution.

1. Baseline Model — Logistic Regression
A logistic regression model was implemented as a simple and interpretable baseline. While it achieved high overall accuracy, it failed to identify most customers who churned.

2. Decision Tree
A decision tree model significantly improved churn detection by capturing nonlinear relationships between customer behavior and cancellation patterns.

3. Tuned Decision Tree (Final Model)
Hyperparameters were optimized to balance detection ability and overfitting. This model provided the strongest ability to detect churners while maintaining operational efficiency.

4. Random Forest
An ensemble model achieved high accuracy but was overly conservative and missed many churn customers, making it less suitable for proactive retention.

# Evaluation

For this business problem, recall for churn customers was the most important metric because failing to detect a customer who leaves results in direct revenue loss.

The tuned decision tree provided the best balance between detecting at-risk customers and minimizing unnecessary interventions. It successfully identified the majority of churn customers while maintaining strong precision.

ROC-AUC analysis confirmed the model’s ability to distinguish between customers who will churn and those who will remain.

# Conclusion

The project demonstrates that machine learning can effectively predict telecom customer churn and enable proactive retention strategies.

By deploying the tuned decision tree model, the company can transition from reactive customer loss management to predictive retention. Early identification of at-risk customers allows targeted engagement efforts that improve customer lifetime value and stabilize revenue growth.

Implementing this model within the customer management workflow can significantly reduce churn and improve long-term business performance.

# REFERENCES
- Worldfolio
- Kaggle
- Productplan.com
- Moringa School classroom resources