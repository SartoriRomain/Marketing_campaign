# Marketing Campaign Report

## Overview
This repository contains an analysis of customer data for a marketing campaign. The objective is to segment customers, evaluate predictive models, and determine the optimal targeting strategy to maximize profitability.

## Contents
- **`Markting_campaign_report.ipynb`**: Jupyter Notebook containing data analysis, customer segmentation, predictive modeling, and profit curve evaluation.
- **`marketing_campaign.csv`**: Dataset including customer demographics, purchasing behavior, and marketing campaign interactions.
- **Visualizations**: Key charts such as missing values analysis, segmentation clustering, confusion matrices, ROC curves, and profit curves.

## Key Analyses
1. **Data Exploration & Cleaning**: Handling missing values and understanding key features.
2. **Customer Segmentation**: Applying Self-Organizing Maps (SOM) and K-Means clustering to categorize customers.
3. **Predictive Modeling**: Comparing Logistic Regression and Random Forest models using confusion matrices and ROC curves.
4. **Profit Curve Analysis**: Identifying the optimal percentage of customers to contact for maximum profitability.

## How to Use
- Clone the repository and navigate to the project folder.
- Open `Markting_campaign_report.ipynb` in Jupyter Notebook.
- Execute the cells sequentially to explore the analysis and insights.
- Modify segmentation thresholds or model parameters as needed for further optimization.

## Business Insights
- **Effective customer segmentation enhances targeted marketing strategies.**
- **Logistic Regression is cost-efficient for limited budgets, whereas Random Forest maximizes overall profitability.**
- **The profit curve analysis suggests contacting 28% of customers for efficiency or 42% for broader outreach.**

## Requirements
- Python 3.x
- Required Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `minisom`

## Author
This analysis was conducted to optimize marketing campaign performance using data-driven decision-making.

