# Predictive Analysis of Medical Students' Susceptibility to Diabetes

## Introduction
Welcome to my LHL Final Project, where we delve deep into a predictive analysis of medical students' risk of developing diabetes.

## Data Source and Objectives
I started by sourcing a database from Kaggle that consists of data for 200,000 students, providing an extensive record of their health conditions. However, there was a notable portion of data that was absent. From this, I formulated two central goals:
1. Utilize the current data to train a model that would then predict the missing diabetes data (approximately 20,000 entries).
2. Conduct regression analysis on the filled data to discern health attributes that play a role in the emergence of diabetes.

## Methodology
To realize the aforementioned objectives, I undertook the following procedures:
1. **Data Cleaning & EDA**: Ensured data quality and explored initial insights.
2. **Model Training**: I began with Logistic Regression and Random Forest. But due to unsatisfactory results, I shifted to XGBoost, attaining an accuracy of 89% in predicting missing data.
3. **Regression Analysis**: Searched for correlations between different features and the likelihood of diabetes.
4. **Visualization**: Used Tableau to represent the data in an intuitive manner.

## Key Findings
From the regression models and visualizations, several observations emerged:
- **Logistic Regression**: 
  - There's a strong negative correlation with gender, indicating a lower susceptibility for females.
  - Blood type O exhibited a negative relation with diabetes.
  - Non-smokers had a diminished risk.
  - Factors like Blood type B, Blood pressure, Cholesterol, Heart rate, Blood type A, and Body temperature had a positive correlation.
  
- **Tableau Visualizations**:
  - Factors like smoking, gender, and blood type exerted limited influence.
  - Data revealed that individuals with reduced body temperature, height, and blood pressure were at an increased risk, while those with a higher weight, cholesterol, heart rate, age, and BMI showed augmented susceptibility.

## Challenges Faced
The course of this project was not without hurdles:
1. Mismatch between database metadata and its content led to swift adjustments in project goals.
2. Encountered hard-to-spot duplicates, necessitating a restart.
3. Weak correlations between data features and the predictive outcome.
4. Large volumes of missing data that complicated training.

## Future Directions
For further refinement of this project, the following paths can be explored:
1. Broaden the dataset to include non-medical student populations.
2. Execute rigorous duplication checks, particularly on potential primary key columns.
3. Fine-tune the predictive model to better capture nuances.
4. Foster collaborations with healthcare professionals to gain medically accurate insights.
