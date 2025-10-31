# Telecom Customer Churn Analysis  
This project aims to analyze the churn rate of a telecom company, Orange S.A., and identify the factors that contribute to customer churn. The dataset used in this analysis is the Orange Telecom’s Churn Dataset, which includes cleaned customer activity data and a churn label indicating whether a customer cancelled their subscription.

## Problem Statement  
The problem addressed in this project is the customer churn rate in Orange Telecom. Customer churn refers to the number of customers who discontinue their subscription within a specific period. The objective is to explore and analyze the data to uncover the key factors responsible for customer churn. Based on the findings, recommendations will be provided to enhance customer retention.

## Business Objective  
The primary business objective of this project is twofold:

- Identify the key factors contributing to customer churn: By analyzing the customer activity data, we aim to identify patterns and correlations that indicate why customers are cancelling their subscriptions.  
- Provide recommendations for customer retention: Based on the analysis results, we will propose actionable recommendations to Orange Telecom for retaining valuable customers. These recommendations may include targeted marketing campaigns, improved customer service, or service enhancements to address identified pain points.

## Project Structure  
The project repository follows a standard structure for organizing the code and related files:

**data**: This directory contains the dataset files used for the analysis.  
**notebooks**: This directory contains Jupyter notebooks used for data exploration, analysis, and modelling.  
**scripts**: This directory includes Python scripts developed for data preprocessing, feature engineering, and model evaluation.  
**reports**: This directory contains the project reports and visualisations generated during the analysis.  
**README.md**: This file provides an overview of the project, its objectives, and the project structure.  
**requirements.txt**: This file lists the required Python libraries and their versions for reproducing the project environment.

## Getting Started  

### Prerequisites  
- Python 3.7+  
- Key libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost` (optional)  
- Dataset file(s) placed in `data/` directory  

### Installation  
```bash
git clone https://github.com/your-username/telecom-customer-churn-analysis.git  
cd telecom-customer-churn-analysis  
pip install -r requirements.txt

Directory Structure
telecom-customer-churn-analysis/
│
├── data/
│   └── churn_dataset.csv
├── notebooks/
│   └── exploratory_analysis.ipynb
├── scripts/
│   ├── preprocess.py
│   ├── feature_engineering.py
│   └── model_training.py
├── reports/
│   └── churn_insights_report.pdf
├── requirements.txt
└── README.md



