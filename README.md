# Youth Employment Prediction

## Project Overview
Analysis of youth employment outcomes in South Africa using advanced machine learning techniques. This project applied **Random Forest** and **XGBoost classifiers** to predict employment status from labor market survey data, following the **Team Data Science Process (TDSP)** lifecycle. The solution was recognized among the **Top 10 South African submissions** in the [Zindi - Predictive Insights competition](https://zindi.global/competitions/predictive-insights-youth-income-prediction-challenge), demonstrating both technical excellence and real‑world impact.

---

## 1. Business Understanding

### Problem Definition
Youth unemployment is a critical challenge in South Africa. The goal of this project was to build predictive models that identify employment outcomes based on demographic and labor market features, enabling data‑driven insights for policy and decision‑making.

### Scope
- Development of two binary classification models (Random Forest, XGBoost).  
- Evaluation using **ROC AUC** as the primary performance metric.  

---

## 2. Data Acquisition & Understanding

- **Source:** Four rounds of youth labor market surveys conducted at 6‑month intervals.  
- **Content:** Numerical, categorical, and text responses, including demographics (age, gender, education) and labor market features (province, geography, tenure, school quintile).  
- **Exploration:** Statistical analysis and visualizations to uncover distributions, correlations, and feature importance.  

---

## 3. Modeling

### Feature Engineering
- Preprocessing: Missing value handling, categorical encoding, and standardization.  
- Feature creation: Derived variables to enhance predictive power.  

### Model Training
- Random Forest Classifier.  
- XGBoost Classifier with **GridSearchCV** hyperparameter tuning.  

### Model Evaluation
- Random Forest ROC AUC: **0.8244**  
- XGBoost ROC AUC: **0.8561**  
- Feature importance and mutual information analysis highlighted key drivers such as **gender, province, geography, tenure, and education level**.  

---

## 4. Key Findings

Exploratory data analysis surfaced several actionable insights into the factors driving youth employment outcomes in South Africa:

- **Geography matters:** Urban candidates were significantly more likely to be employed than those from rural or suburban areas, pointing to structural inequality in labour market access.  
- **Regional disparity:** Western Cape had the highest employment rate among all provinces, while North West had the lowest -highlighting the uneven distribution of economic opportunity across the country.  
- **Gender gap:** Male candidates outperformed female candidates in employment outcomes, with females making up approximately 56% of survey participants yet achieving lower employment rates.  
- **Education and funding:** Candidates who attended better-funded schools (quintile 1 & 2) showed stronger employment outcomes, despite those quintiles being associated with lower-income communities - suggesting school quality plays a meaningful role beyond socioeconomic background.  
- **Tenure effect:** The tenure distribution was right-skewed, with most individuals having short prior work experience, indicating that prior exposure to the labour market is a differentiating factor.  

These findings go beyond model performance - they provide a foundation for targeted interventions and evidence-based policy recommendations.

---

## 5. Project Setup

### File Structure

├── youth_employment.ipynb   # Main notebook (EDA, modelling, predictions)
├── README.md
└── LICENSE

### Execution Flow
1. Data Preparation  
2. Data Exploration  
3. Feature Engineering  
4. Model Training  
5. Model Evaluation  
6. Predictions  

### Environment
- Python 3 in Google Colab.  
- Approximate runtime: ~4 minutes (longer for XGBoost tuning).  

---

## Conclusion
This project demonstrates the application of machine learning to a pressing socio‑economic issue: youth unemployment. By combining rigorous data science methodology with advanced modeling, the solution achieved **top‑tier performance in a national competition**. The insights generated provide actionable understanding of the demographic and labor market factors influencing employment, showcasing both technical skill and the ability to deliver impactful, stakeholder‑ready analytics.
