#  Customer Churn Prediction and Customer Segmentation using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-red">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

---

#  Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Predicting which customers are likely to leave helps organizations take proactive measures to improve customer retention.

This project analyzes customer data using **Machine Learning** to:

- Predict whether a customer is likely to churn.
- Segment customers into different groups using clustering.
- Discover important factors influencing customer churn.
- Generate business insights that support customer retention strategies.

The project is implemented using Python and Scikit-learn in Google Colab.

---

#  Objectives

- Perform data cleaning and preprocessing.
- Explore customer behavior using visualizations.
- Segment customers using **K-Means Clustering**.
- Build churn prediction models.
- Compare multiple Machine Learning algorithms.
- Identify the best-performing model.
- Generate business recommendations based on the analysis.

---

#  Dataset

**Dataset Name:**
IBM Telco Customer Churn Dataset

**Source:**
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains customer information including:

- Customer demographics
- Account information
- Internet services
- Contract details
- Payment methods
- Monthly charges
- Total charges
- Churn status

Total Records:

- **7043 Customers**
- **21 Features**

---

#  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

#  Project Workflow

```text
Customer Dataset
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Customer Segmentation
(K-Means Clustering)
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ├── Logistic Regression
        ├── Decision Tree
        └── Random Forest
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
```

---

#  Exploratory Data Analysis

The following analyses were performed:

- Customer Churn Distribution
- Gender vs Churn
- Senior Citizen vs Churn
- Contract Type vs Churn
- Monthly Charges Distribution
- Monthly Charges vs Churn
- Customer Tenure Distribution
- Tenure vs Churn
- Internet Service vs Churn
- Payment Method vs Churn
- Correlation Heatmap

Each visualization is accompanied by observations and business insights.

---

#  Machine Learning Models

The following Machine Learning algorithms were implemented:

### 1️ Logistic Regression

A linear classification algorithm used to predict customer churn.

---

### 2️ Decision Tree

A tree-based supervised learning model for customer classification.

---

### 3️ Random Forest

An ensemble learning algorithm combining multiple decision trees for improved prediction.

---

#  Customer Segmentation

Customer segmentation was performed using:

- **K-Means Clustering**

The optimal number of clusters was determined using the **Elbow Method**.

Clusters were visualized using **Principal Component Analysis (PCA)**.

---

#  Model Performance

| Model | Accuracy |
|---------|---------:|
| Logistic Regression | **81.5%** |
| Random Forest | **79.7%** |
| Decision Tree | **72.6%** |

**Best Performing Model:** Logistic Regression

---

#  Key Findings

The analysis revealed that:

- Customers with **month-to-month contracts** are more likely to churn.
- Customers with **shorter tenure** have higher churn rates.
- Higher **monthly charges** increase the likelihood of churn.
- Customer segmentation helps identify groups with similar characteristics for targeted marketing.
- Logistic Regression achieved the highest accuracy on this dataset.

---

#  Business Recommendations

Based on the analysis, businesses should:

- Encourage customers to switch to long-term contracts.
- Provide loyalty rewards for long-term customers.
- Offer personalized discounts to customers with high monthly charges.
- Focus retention campaigns on customers identified as high-risk.
- Use customer segmentation to design targeted marketing strategies.

---

#  Future Scope

The project can be extended by:

- Implementing XGBoost or LightGBM.
- Performing hyperparameter tuning.
- Deploying the model using Streamlit or Flask.
- Using Explainable AI (SHAP/LIME).
- Integrating real-time customer data.
- Building an interactive dashboard.

---

#  Repository Structure

```text
customer-insights-ml/
│
├── Customer_Churn_Prediction_and_Segmentation.ipynb
├── README.md
├── requirements.txt
```

---

#  How to Run

1. Clone the repository.

```bash
git clone https://github.com/aquariaism/customer-insights-ml
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```text
Customer_Churn_Prediction_and_Segmentation.ipynb
```

4. Download the IBM Telco Customer Churn dataset from Kaggle.

5. Upload the dataset to Google Colab.

6. Run all cells sequentially.

---

#  References

- IBM Telco Customer Churn Dataset (Kaggle)
- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

