# E-commerce Customer Spending Analysis

## Overview

This project explores customer behavior data from an e-commerce platform to understand the factors that influence yearly customer spending.

Using exploratory data analysis and Linear Regression, the project investigates relationships between customer engagement metrics and annual revenue generation.

The goal is to identify which customer behaviors are most strongly associated with higher spending and evaluate how well customer spending can be predicted using machine learning.

---

## Objective

The main objective of this project is to analyze customer engagement metrics and predict yearly customer spending using a Linear Regression model.

The analysis focuses on answering questions such as:

- Does mobile app usage influence customer spending?
- Is website engagement associated with higher revenue?
- Does customer loyalty (membership duration) play a larger role in yearly spending?

---

## Dataset

The dataset contains customer information and engagement metrics, including:

- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (target variable)

---

## Exploratory Data Analysis

Several visualizations were used to explore relationships between variables:

- Jointplots
- Hexbin plots
- Pairplots
- Linear model plots (lmplot)

### Key Insights

- Length of Membership showed the strongest positive relationship with Yearly Amount Spent
- Time on App demonstrated a stronger relationship with spending than Time on Website
- Website usage alone appeared to have a weaker association with customer spending
- Customer retention may play a more important role in revenue generation than platform preference alone

---

## Machine Learning

A Linear Regression model was trained to predict Yearly Amount Spent based on customer engagement metrics.

### Workflow

1. Feature selection
2. Train-test split
3. Model training
4. Prediction
5. Model evaluation
6. Residual analysis

---

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The model achieved a strong fit, and residual analysis suggested that the prediction errors were approximately normally distributed.

---

## Conclusion

The analysis suggests that Length of Membership is the strongest predictor of Yearly Amount Spent, indicating that long-term customers tend to generate significantly more revenue.

Although Time on App showed a stronger relationship with yearly spending than Time on Website, customer retention appears to be the most important factor overall.

These findings suggest that strategies focused on long-term engagement and customer loyalty may have the greatest impact on revenue growth.

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```text
e-commerce_customer_spending_analysis/
│
├── data/
│   └── ecommerce_customers.csv
│
├── e-commerce_customer_spending_analysis.ipynb
│
└── README.md