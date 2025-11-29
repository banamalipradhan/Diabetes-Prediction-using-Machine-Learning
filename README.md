<p align="center">
  <img src="cover page/cover_page.png" width="800" alt="Diabetes Prediction using Machine Learning">
</p>



# Diabetes Prediction using Machine Learning

This project focuses on building a predictive classification model to determine whether an individual is likely to have diabetes based on clinical and demographic data.

---

## Problem Statement

Early diagnosis of diabetes is essential in preventing long-term health issues. Laboratory testing may not always be accessible or affordable.  
This project aims to support early risk detection using a machine-learning model built from easily measurable health indicators.

---

## Objective

- Identify the major factors associated with diabetes
- Build a reliable model to predict diabetes (Yes/No)
- Evaluate performance based on training and testing accuracy
- Provide data-driven support for healthcare decision-making

---

## Dataset Overview

The dataset contains **768 entries** with the following features:

- Pregnancies – Number of times pregnant  
- Glucose – Plasma glucose concentration  
- BloodPressure – Diastolic blood pressure  
- SkinThickness – Triceps skin thickness  
- Insulin – Serum insulin level  
- BMI – Body mass index  
- DiabetesPedigreeFunction – Genetic diabetes likelihood  
- Age – Age in years  
- Outcome – Target variable (1 = diabetic, 0 = non-diabetic)

No missing rows, but some zero medical values represent missing readings and need careful handling for real-world implementation.

---

## Workflow

1. Loaded and inspected dataset structure  
2. Performed exploratory analysis on health-related features  
3. Prepared features and target variable for modeling  
4. Split data into training and testing sets  
5. Trained the model using Logistic Regression  
6. Evaluated accuracy on both sets

---

## Model Performance

| Dataset | Accuracy |
|--------|----------|
| Training Set | 77.19% |
| Testing Set | 75.97% |

The model generalizes well to unseen data with minimal overfitting.

---

## Key Insights

- High glucose levels strongly correlate with diabetes presence
- BMI, age, and family health history also influence diabetes risk
- Insulin-related missing values can impact model reliability
- Several medical attributes require careful preprocessing for deployment

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Jupyter Notebook  


## Author
**Banamali Pradhan** — Aspiring Data Analyst  
Transitioning from Pharmaceutical Industry to Data Analytics  
[LinkedIn Profile](https://www.linkedin.com/in/banamali-pradhan)
