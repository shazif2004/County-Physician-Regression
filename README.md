# County-Level Physician Analysis Using Multiple Linear Regression

This repository contains my **STA 108 Final Project**, where I analyze factors associated with the number of physicians across U.S. counties using multiple linear regression techniques.

## 📊 Dataset
- **Source:** County Data Indicators (CDI)
- **Observations:** 440 U.S. counties
- **Response Variable:**  
  - Number of physicians per county
- **Predictors:**  
  - Population  
  - Total personal income (in millions)  
  - Land area  
  - Percent of population aged 65+  
  - Hospital beds  

## 🧠 Methods Used
- Multiple Linear Regression
- Correlation and scatterplot analysis
- Model comparison using R² and adjusted R²
- Residual diagnostics (QQ plots, residual vs fitted)
- Interaction terms
- Partial R² analysis
- Partial F-tests for nested models

## 📈 Key Findings
- Population and total personal income explain most of the variation in physician counts.
- Population and income are highly correlated, indicating multicollinearity.
- After controlling for population and income, **hospital beds** add the most explanatory power.
- Interaction terms slightly improve model fit but reduce interpretability.
- Models explain approximately **90% of the variation** in physician counts.

## 🛠 Tools
- **Language:** R
- **Techniques:** Linear modeling, diagnostics, hypothesis testing
