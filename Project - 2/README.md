# Tobacco Use and Mortality Machine Learning Project

## Project Overview

This project involves analyzing the relationship between tobacco use and mortality rates. The goal is to predict the likelihood of mortality based on various factors related to tobacco use, such as smoking patterns, demographics, and health conditions. The project utilizes machine learning algorithms to build predictive models that can help in understanding and mitigating the health impacts of smoking.

### About the Dataset

The dataset used in this project includes data on tobacco use and mortality, collected from various surveys and health organizations. It also includes socioeconomic data, such as age, gender, income, education level, occupation, and health-related factors.

### Context

In 2014-2015, smoking-related conditions caused 1.7 million hospital admissions in England for adults aged 35 and over. This project aims to explore the health issues associated with smoking, such as smoking prevalence, habits, behaviors, smoking-related health issues, and mortality.

### Project Objectives

- **Predict the likelihood of mortality** based on tobacco use patterns and related factors.
- Explore the effects of demographic, socioeconomic, and health-related factors on mortality rates.

---

## Dataset

The dataset for this project contains various factors, including:

- **Tobacco Use Data**: Smoking habits, frequency, duration, and types of tobacco used.
- **Health Data**: Pre-existing health conditions, healthcare access, and lifestyle factors.
- **Socioeconomic Data**: Information about the individual's age, gender, income, education, and occupation.
- **Mortality Data**: Data on the relationship between smoking and mortality, including historical data on causes of death.

---

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, seaborn, matplotlib
- **Frameworks for Deployment**:  Streamlit
- **Visualization Tools**: Power BI

---

## Project Phases

### 1. **Problem Definition**
   - Objective: Predict the likelihood of mortality based on tobacco use and related factors.
   - Scope: Focus on a specific demographic or geographic region if necessary.
   
### 2. **Data Collection**
   - National Health and Nutrition Examination Survey (NHANES)
   - Behavioral Risk Factor Surveillance System (BRFSS)
   - Mortality Data from the WHO and CDC
   - Tobacco Use Data from various surveys
   
### 3. **Data Preprocessing**
   - Clean the data by handling missing values and outliers.
   - Merge datasets from different sources to form a comprehensive dataset.
   - Create features related to tobacco use, demographics, and health-related factors.
   
### 4. **Exploratory Data Analysis (EDA)**
   - Visualizations: Histograms, scatter plots, and heatmaps.
   - Statistical Analysis: Identify correlations between features and mortality.

### 5. **Model Selection**
   - Algorithms: Logistic Regression, Decision Trees, Random Forests, Gradient Boosting (XGBoost, LightGBM), Support Vector Machines, and Neural Networks.
   
### 6. **Model Training and Evaluation**
   - Split data into training and testing sets.
   - Evaluate using accuracy, precision, recall, F1-score, and ROC-AUC score.
   - Use cross-validation and hyperparameter tuning to optimize model performance.

### 7. **Model Interpretation**
   - Feature Importance: Identify which features have the most significant impact on predicting mortality.
   - Explainability: Use SHAP or LIME for model interpretability.

### 8. **Deployment**
   - API development using Flask or FastAPI.
   - Web application using Streamlit .

### 9. **Monitoring and Maintenance**
   - Continuously monitor the model's performance.
   - Update the model regularly with new data to ensure accuracy.

### 10. **Documentation and Reporting**
   - Maintain project documentation with clear explanations of the data, methods, and results.
   - Create visual reports to communicate insights to stakeholders.

---

## Acknowledgements

- The data for this project has been sourced from official health organizations such as the World Health Organization (WHO) and the Centers for Disease Control and Prevention (CDC).
- The statistical models and feature engineering techniques are based on research and articles in the field of healthcare analytics.

---


