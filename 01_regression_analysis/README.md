# Italian Household Expenditure Analysis (Multiple Linear Regression)

## Project Overview

This project investigates the key socio-economic and demographic factors influencing monthly household expenditure in Italy.  
The analysis is conducted using multiple linear regression models applied to official ISTAT microdata on household consumption.

The goal is to quantify how geographic, occupational, and household structure variables affect spending behavior and to evaluate the robustness of the econometric model.

---

## Objectives

- Identify the main determinants of household expenditure in Italy  
- Quantify the impact of socio-economic and demographic factors  
- Compare alternative regression specifications  
- Validate model assumptions using statistical tests  
- Improve model reliability using robust methods (FGLS)

---

## Dataset

The dataset is based on publicly available ISTAT microdata on Italian household consumption.

### Variables

**Dependent Variable**
- Monthly household expenditure (EUR)

**Independent Variables**
- Geographic area of residence  
- Household composition  
- Employment status of reference person  
- Type of expenditure  

---

## Methodology

The analysis follows a standard econometric and statistical workflow:

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Data type conversion
   - Factor encoding for categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Boxplots by expenditure categories
   - Descriptive statistics

3. **Econometric Modeling**
   - Multiple Linear Regression (OLS)
   - Model specification testing
   - Alternative model comparisons

4. **Model Evaluation**
   - ANOVA-based model comparison
   - AIC-based model selection

5. **Diagnostic Tests**
   - Normality of residuals (Jarque-Bera test)
   - Heteroskedasticity (Breusch-Pagan test)
   - Autocorrelation (Durbin-Watson test)

6. **Robust Estimation**
   - Robust standard errors (HC0 estimator)
   - Feasible Generalized Least Squares (FGLS)

---

## Key Results

- Geographic area significantly influences household expenditure patterns  
- Household composition is a strong predictor of consumption levels  
- Employment status affects expenditure variability  
- Significant heteroskedasticity detected and addressed through robust methods  
- FGLS improves model efficiency under heteroskedastic conditions  

---

## Tools & Technologies

- R
- tidyverse
- ggplot2
- lm (linear regression)
- tseries
- lmtest
- sandwich

---

## Key Insights

- Household expenditure is strongly driven by structural socio-economic factors  
- Regional disparities in Italy remain significant in consumption behavior  
- Model diagnostics highlight the importance of robust estimation techniques  
- Econometric validation improves interpretability and reliability of results  

---


## Author

**Martina Tenace**  
MSc Student in Business Analytics & Data Science  
University of Chieti-Pescara  

---

## Contact

LinkedIn: https://www.linkedin.com/in/martina-tenace-497a66308
