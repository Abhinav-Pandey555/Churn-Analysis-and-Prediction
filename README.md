# 📊 Telecom Customer Churn Analysis & Prediction Dashboard

This repository contains an end-to-end **Telecom Customer Churn Analysis and Prediction** project built using **Microsoft SQL Server, Python, and Power BI**. The project combines interactive business intelligence dashboards with a machine learning model to help identify customers at risk of churning and support data-driven retention strategies.

---

## 🔍 Project Overview

The primary objective of this project is to analyze historical customer behavior, identify the factors contributing to customer churn, and predict future churn using a **Random Forest Classifier**.

The solution follows a complete analytics workflow:

* Data extraction and cleaning using **Microsoft SQL Server**
* Data transformation and preparation using **Power Query**
* Customer churn prediction using **Python (Random Forest)**
* Interactive dashboard development using **Power BI**
* Business insights generated through advanced **DAX measures** and visualizations

### 🔄 ETL & Data Preparation

* Data extracted, cleaned, and validated using SQL queries in SQL Server.
* Missing values, duplicate records, and inconsistent data handled during preprocessing.
* Additional transformations performed using Power Query in Power BI.
* Data model designed with optimized relationships between multiple tables.

### 🤖 Customer Churn Prediction

* Built a **Random Forest Classifier** to predict customer churn.
* Performed feature engineering and preprocessing before model training.
* Evaluated model performance using classification metrics.
* Achieved an overall prediction accuracy of **84%**.
* Generated churn predictions that can be integrated into business reporting for proactive customer retention.

### 📈 Power BI Dashboard

The dashboard provides interactive insights into customer behavior and churn trends through:

* KPI Cards
* Doughnut Charts
* Line Charts
* Stacked Column Charts
* Clustered Bar Charts
* Matrix Tables
* Interactive Filters and Slicers
* Customer Segmentation Analysis
* Churn Rate Analysis
* Revenue and Customer Distribution
* Risk Category Visualization based on churn prediction

### 📊 DAX & Business Intelligence

* Custom DAX Measures for KPIs and business metrics
* Dynamic calculations for churn percentage
* Customer segmentation metrics
* Interactive filtering and cross-highlighting
* Performance optimization using efficient data modeling



<img width="1161" height="656" alt="Screenshot 2026-07-08 232244" src="https://github.com/user-attachments/assets/d85eb132-b7a4-4d6a-af67-dfc0340b0294" />

---

## 🤖 Machine Learning Workflow

1. Data Collection from SQL Server
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Train-Test Split
5. Random Forest Model Training
6. Model Evaluation
7. Customer Churn Prediction
8. Visualization of Predictions in Power BI

---

## 📈 Model Performance

| Metric          | Value                    |
| --------------- | ------------------------ |
| Algorithm       | Random Forest Classifier |
| Accuracy        | **84%**                  |
| Problem Type    | Binary Classification    |
| Target Variable | Customer Churn           |

The model was evaluated using standard classification metrics, including:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🛠 Tools & Technologies

| Tool                 | Purpose                                     |
| -------------------- | ------------------------------------------- |
| Microsoft SQL Server | Data extraction, cleaning, and preparation  |
| Python               | Data preprocessing and machine learning     |
| Pandas & NumPy       | Data manipulation and preprocessing         |
| Scikit-learn         | Random Forest model training and evaluation |
| Power Query          | Data transformation                         |
| DAX                  | Business logic and KPI calculations         |
| Power BI             | Dashboard development and visualization     |

---

## 📊 Dashboard Insights

The dashboard helps answer key business questions such as:

* What is the overall customer churn rate?
* Which customer segments are most likely to churn?
* Which contract types have the highest churn?
* How do monthly charges impact customer churn?
* Which payment methods are associated with higher churn?
* Which customers are predicted to churn based on the machine learning model?
* What customer groups should the business target for retention campaigns?

---

<img width="1158" height="652" alt="Screenshot 2026-07-08 232412" src="https://github.com/user-attachments/assets/861a6e32-0580-4299-b282-c1438dbe9cb4" />


## 📌 How to View the Dashboard

1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Explore the interactive dashboard using filters and slicers.
4. Review the churn prediction insights alongside historical customer analysis.

---

## 🚀 Project Outcome

This project demonstrates an end-to-end business intelligence and machine learning solution by combining:

* SQL-based data preparation
* Power Query transformations
* Advanced DAX calculations
* Predictive analytics using Random Forest
* Interactive Power BI dashboards

The final solution enables businesses to identify high-risk customers, understand the key drivers of churn, and make data-driven decisions to improve customer retention.
