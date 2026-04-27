# Medical Insurance Cost Analysis

## Overview

This project analyzes how demographic and lifestyle factors influence medical insurance charges. 

The analysis combines exploratory data analysis (EDA) with machine learning to identify key cost drivers and understand patterns in healthcare expenses.

---

## Objective

To investigate which factors most significantly impact medical insurance costs and evaluate how well these costs can be predicted using simple and advanced models.

---

## Dataset

The dataset contains 1,338 individual records with the following features:

- **age**: age of the individual  
- **sex**: gender  
- **bmi**: body mass index  
- **children**: number of dependents  
- **smoker**: smoking status  
- **region**: residential area  
- **charges**: medical insurance cost (target variable)  

---

## Key Findings

- Medical charges are highly right-skewed, with a small group responsible for disproportionately high costs  
- Smoking is the most significant factor, with smokers incurring substantially higher expenses  
- Age and BMI are positively associated with charges, especially among smokers  
- BMI alone shows a weak relationship, but becomes more relevant when combined with smoking status  

---

## Machine Learning

Two models were implemented to predict medical charges:

### Linear Regression
- MAE: ~$4,181  
- Captures general trends but struggles with non-linear relationships  

### Random Forest Regressor
- MAE: ~$2,550  
- Significantly improves performance by capturing non-linear patterns and interactions  

### Feature Importance (Random Forest)

- Smoking status is the dominant predictor (~60% importance)  
- BMI and age are secondary drivers  
- Other variables have minimal impact  

---

## Conclusion

The analysis shows that medical insurance costs are primarily driven by lifestyle factors, particularly smoking. 

While demographic variables such as age and BMI also influence costs, their effects are significantly amplified among smokers.

The results demonstrate the importance of combining exploratory analysis with machine learning to uncover meaningful patterns in real-world data.




