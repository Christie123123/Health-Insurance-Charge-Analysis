# Health Insurance Charge Analysis

## Project Overview
This project investigates how smoking impacts medical charges covered by insurance companies and explores other factors contributing to variations in medical costs. The study leverages statistical modeling and regression techniques to analyze the influence of demographic and health-related factors.1

## Dataset
The dataset used in this study is the **Medical Cost Personal Datasets** from Kaggle, originally published by Miri Choi in 2017. It contains information on insurance beneficiaries, including:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Residential region
- Medical charges

## Research Questions
### Primary Question:
- How does smoking status affect a person’s medical expenses?

### Exploratory Question:
- What are the top three leading factors influencing medical costs billed by insurance?

## Methodology
1. **Data Preprocessing**
   - Standardization of continuous variables
   - Encoding categorical variables
   - Splitting dataset into training (80%) and testing (20%) sets

2. **Statistical Models Used**
   - **Linear Regression**: Establishes baseline relationships between predictors and medical charges.
   - **Ridge Regression**: Regularization to reduce variance and address multicollinearity.
   - **Lasso Regression**: Feature selection by eliminating less important variables.

3. **Model Evaluation**
   - R-squared and Adjusted R-squared
   - Root Mean Squared Error (RMSE)
   - Hypothesis testing (ANOVA, t-tests)

## Key Findings
- **Smoking is the most significant predictor of higher medical charges.**
- **Age and BMI also have strong positive relationships with medical costs.**
- **Sex and residential region have minimal impact on medical charges.**
- **Ridge and Lasso regression did not significantly outperform linear regression, suggesting limited multicollinearity.**

## Limitations & Future Research
- The models assume a **linear relationship**, which may not fully capture complex interactions between variables.
- Future studies could explore **non-linear models** (e.g., neural networks) for better predictive performance.
- The dataset is limited to a specific population and may not generalize to other healthcare systems.
