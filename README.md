# Telecom Customer Churn Prediction

**Tools:** Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  
**Problem Type:** Classification  
**Industry:** Telecommunications  

---

## Project Overview

Customer churn directly impacts recurring revenue for subscription-based telecom businesses.

This project builds a machine learning model to predict which customers are most likely to cancel their service and identifies key behavioral and service-related drivers of churn. The goal is to support proactive retention strategies.

---

## Business Problem

Telecom companies rely heavily on long-term customer subscriptions. When customers cancel their service, companies lose both immediate revenue and long-term customer value.

The objective of this project is to:

* Predict customers at high risk of churn  
* Identify key drivers influencing churn behavior  
* Translate model results into actionable retention insights  

---

## Dataset

This project uses the **Maven Analytics Telecom Customer Churn dataset**, representing customer data at the end of **fiscal Q2 2022**.

Each row represents a unique telecom customer and includes:

* Customer demographics  
* Contract information  
* Internet service details  
* Billing and pricing data  
* Service usage metrics  

---

## Project Workflow

1. **Data Preparation**
   * Validated missing values
   * Created churn target variable
   * Removed identifier and leakage columns

2. **Exploratory Data Analysis**
   * Identified key churn drivers
   * Analyzed churn across customer segments

3. **Feature Engineering**
   * Addressed multicollinearity
   * Encoded categorical variables

4. **Model Development**
   * Logistic Regression
   * Random Forest classifier
   * ROC-AUC evaluation and threshold tuning

---

## Key Insights

* **Month-to-month contracts** show the highest churn rates  
* **Fiber internet customers** exhibit elevated churn risk  
* **Manual payment methods** correlate with higher churn  
* **Short-tenure customers** are significantly more likely to leave  

---

## Model Results

Two models were evaluated:

* Logistic Regression  
* Random Forest  

The **Random Forest model achieved the strongest predictive performance** and was selected as the final model.

Evaluation metrics included:

* ROC-AUC  
* Precision & Recall  
* Confusion Matrix  

---

## Business Recommendations

Based on the analysis, telecom providers could reduce churn by:

* Encouraging customers to move to longer-term contracts  
* Improving retention strategies for Fiber internet customers  
* Promoting automated payment methods  
* Strengthening onboarding for new customers  

---

## Repository Structure

```
telecom-customer-churn-prediction
│
├── telecom_churn_analysis.ipynb
├── README.md
└── images/
```

---

## Author

Data science portfolio project focused on applying machine learning to business problems such as **customer retention and revenue optimization**.
