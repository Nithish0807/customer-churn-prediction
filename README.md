# customer-churn-prediction using Machine Learning
Machine learning project to predict telecom customer churn using Python and scikit-learn.

## Project Overview

Customer churn is a critical problem for subscription-based businesses such as telecom, streaming, and SaaS companies.
This project builds a machine learning model that predicts whether a telecom customer is likely to churn based on their subscription details and service usage patterns.

By identifying customers who are likely to leave the service, companies can take proactive measures to improve customer retention and reduce revenue loss.

Project Type: Machine Learning Classification Project
---

## Problem Statement

Customer churn refers to customers discontinuing a company's service. High churn rates can significantly impact business revenue and growth.

The objective of this project is to develop a machine learning model that predicts customer churn using historical telecom customer data.

---

## Dataset

The dataset used in this project contains telecom customer information including:

* Customer demographics
* Contract type
* Internet service type
* Payment method
* Monthly charges
* Tenure
* Customer churn status

Each row represents one customer and the **Churn** column indicates whether the customer left the service.

Dataset size:

* **7043 customers**
* **20+ features**

Dataset Source: Telecom Customer Churn Dataset

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab


## Skills Demonstrated

- Data preprocessing
- Feature encoding
- Machine learning modeling
- Model evaluation
---

## Machine Learning Models

The following models were used in this project:

* Logistic Regression
* Random Forest Classifier

These models were trained and evaluated using a train-test split approach.

---

## Project Workflow

The workflow of the project includes:

1. Data Loading
2. Data Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis
9. Prediction Results

---

## Model Evaluation

The models were evaluated using the following metrics:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

These metrics help measure how well the model predicts customer churn.

---

## Key Insights

Analysis of feature importance shows that the following factors strongly influence customer churn:

* Contract type
* Monthly charges
* Customer tenure
* Internet service type

Customers with **month-to-month contracts and higher monthly charges** tend to have a higher churn probability.

---

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn using telecom customer data.
The model can help businesses identify high-risk customers and implement strategies to improve customer retention.

---

## Repository Structure

```
customer-churn-prediction/
│
├── customer_churn_prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

---

## Author

Nithish
This project was developed as part of a data science portfolio project.
