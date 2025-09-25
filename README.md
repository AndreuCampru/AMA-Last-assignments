# AMA – Last Assignments

This repository contains the final assignments for the **Advanced Multivariate Analysis (AMA)** course.  
The work covers two applied case studies using statistical modelling and machine learning techniques:

---

## 1. Generalized Additive Models (GAM) for Hirsutism Data

This study analyzes data from a clinical trial evaluating the effectiveness of an anti-androgen combined with an oral contraceptive in reducing hirsutism over 12 months.  

- **Dataset**: Patients’ hirsutism levels, measured by the modified Ferriman–Gallwey scale, along with baseline clinical variables (blood pressure, weight, height).  
- **Objective**: Model the degree of hirsutism after 12 months (`FGm12`) as a function of baseline characteristics and treatment level.  
- **Methods**: Several GAMs (including semiparametric models) are fitted and compared using summaries, diagnostic plots, and ANOVA tests.  
- **Outcome**: Identification of the most appropriate models for explaining treatment effectiveness while capturing nonlinear relationships.

---

## 2. Interpretability and Explainability in Machine Learning – Concrete Data

This assignment applies explainable ML techniques to the **Concrete Compressive Strength dataset** from the UCI Machine Learning Repository.  

- **Dataset**: 1,030 observations, with compressive strength as the response variable and eight input features (cement, slag, fly ash, water, superplasticizer, coarse aggregate, fine aggregate, and age).  
- **Objective**: Model concrete compressive strength and explore the interpretability of model predictions.  
- **Methods**:
  - Fit and compare **Random Forest, Linear Model, and GAM**.  
  - Compute variable importance using impurity reduction, permutation methods, Shapley values, and ghost variables.  
  - Use **DALEX** for global explanations (variable importance, PDPs, local dependence plots).  
  - Apply local explainers (SHAP, break-down plots, LIME, ICE plots) to interpret predictions for specific test cases.  
- **Outcome**: Insights into how different ingredients and age contribute to concrete strength, with a focus on interpretability across models.

---

## Keywords

- Statistical Modelling  
- Generalized Additive Models (GAM)  
- Machine Learning  
- Interpretability & Explainability  
- Hirsutism Clinical Trial  
- Concrete Compressive Strength  

---

This repository showcases applied work at the intersection of **statistical methods and interpretable machine learning**, with case studies from **biostatistics** and **civil engineering**.
