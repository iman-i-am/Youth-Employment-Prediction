# Youth Employment Prediction

## Project Overview
Analysis of youth employment outcomes in South Africa using advanced machine learning techniques. This project applied **Random Forest** and **XGBoost classifiers** to predict employment status from labor market survey data, following the **Team Data Science Process (TDSP)** lifecycle. The solution was recognized among the **Top 10 South African submissions** in the Zindi - Predictive Insights competition, demonstrating both technical excellence and real‑world impact.

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

## 4. Project Setup
### File Structure
- **Data**: Raw and submission files (not shared publicly).  
- **Code**: Google Colab notebooks.  
- **Docs**: Documentation including this README.  

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
