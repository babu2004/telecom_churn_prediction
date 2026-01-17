# Customer Churn Prediction (Machine Learning Zoomcamp)


## Problem Statement

Customer churn refers to customers discontinuing a service. The goal of this project is to **predict whether a customer will churn (Yes/No)** based on demographic information, account details, and service usage patterns.

This is a **binary classification problem**, and accurate predictions can help businesses take proactive retention actions.

---

## Dataset

The project uses the **Telco Customer Churn Dataset**, which contains information about customers such as:

* Demographics (gender, senior citizen, partner, dependents)
* Account details (tenure, contract type, payment method)
* Services subscribed (internet service, online security, streaming)
* Target variable: `churn`

The dataset includes both **categorical and numerical features**, requiring proper preprocessing before model training.

---

## Approach

The overall approach followed in this project:

1. **Data Exploration & Cleaning**

   * Handling missing values
   * Converting data types
2. **Feature Engineering**

   * Encoding categorical variables
   * Scaling numerical features
3. **Model Training**

   * Logistic Regression
   * Tree-based models for comparison
4. **Model Evaluation**

   * Accuracy
   * ROC-AUC score
5. **Model Deployment**

   * Exporting the trained model
   * Serving predictions via a REST API

---

## Results

The models were evaluated using **ROC-AUC** to effectively measure performance on imbalanced data.

* Logistic Regression achieved a strong baseline performance
* Tree-based models provided slight improvements

The final selected model demonstrates reliable predictive performance suitable for deployment.

---

## Key Learnings

* End-to-end machine learning workflow for classification problems
* Handling categorical features in real-world datasets
* Importance of proper evaluation metrics like ROC-AUC
* Basics of deploying ML models as APIs
* Writing clean and reproducible ML code

---

## Future Improvements

* Hyperparameter tuning for improved performance
* Feature selection and importance analysis
* Deploying the model using Docker and cloud platforms

