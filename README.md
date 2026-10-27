# Scrap_Characterization
Statistical modeling project for steel scrap yield analysis using Multiple Linear Regression, PCA, PLS, Ridge, and Lasso. Focused on model diagnostics, data quality assessment, simulation, and predictive analytics within a real manufacturing environment.

# Steel Scrap Yield Modeling

## Overview

This project focused on understanding and estimating the yield contribution of different scrap materials used in steel manufacturing. The objective was to determine whether production outcomes could be explained and predicted from the composition and characteristics of the scrap blend used in different steel formulations.

Beyond predictive performance, the project served as an opportunity to apply statistical modeling, dimensionality reduction, and data validation techniques in a real industrial environment.

---

## Business Problem

Steel production processes use different combinations of scrap materials as raw inputs. The goal of this project was to understand how variations in scrap composition affected the final production yield and to identify the variables that had the greatest impact on process performance.

A secondary objective was to evaluate whether predictive models could be used to estimate yield and support operational decision-making.

---

## Methodology

The project followed a structured analytical workflow:

### 1. Data Understanding and Exploration

- Exploratory Data Analysis (EDA)
- Distribution analysis
- Variable profiling
- Missing value assessment
- Outlier identification

### 2. Feature Analysis

- Correlation analysis
- Multicollinearity assessment
- Variable reduction
- Feature selection

The original dataset contained approximately 25–26 variables. Multiple approaches were used to reduce complexity while preserving explanatory power.

### 3. Statistical Modeling

The following techniques were evaluated:

- Multiple Linear Regression (OLS)
- Principal Component Analysis (PCA)
- Partial Least Squares (PLS)
- Ridge Regression
- Lasso Regression

Models were developed using Python and Statsmodels, with a strong emphasis on interpretability and statistical validation.

---

## Model Evaluation

Several statistical diagnostics and performance indicators were analyzed throughout the project:

- R²
- Adjusted R²
- p-values
- Residual analysis
- Kurtosis
- Variable significance
- Multicollinearity indicators
- Model assumptions validation

Different model configurations were compared to identify the best balance between predictive performance and interpretability.

---

## Tools and Technologies

### Programming & Analytics

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-Learn
- Matplotlib

### Techniques

- Multiple Linear Regression
- PCA
- Partial Least Squares (PLS)
- Ridge
- Lasso
- Simulation-Based Validation

---

## Results

The project identified several statistically relevant relationships within the process and generated useful operational insights.

However, predictive performance on real production data remained limited, with maximum observed R² values near 0.25.

Interestingly, controlled simulations produced significantly stronger results, suggesting that model limitations were likely associated with:

- Data quality issues
- Sampling inconsistencies
- Measurement variability
- Unobserved process factors

Rather than indicating a modeling failure, the results highlighted the importance of understanding the data-generation process before increasing model complexity.

---

## Key Learnings

One of the most valuable outcomes of this project was recognizing that model performance is often constrained more by data quality than by algorithm selection.

Key lessons included:

- The importance of validating statistical assumptions.
- Understanding the impact of multicollinearity.
- Balancing model complexity and interpretability.
- Using simulations to investigate unexplained behavior.
- Recognizing when business and operational processes become the primary source of uncertainty.

---

## Skills Demonstrated

- Statistical Modeling
- Multiple Linear Regression
- Machine Learning Fundamentals
- Predictive Analytics
- PCA
- Partial Least Squares (PLS)
- Feature Selection
- Data Quality Assessment
- Residual Analysis
- Model Validation
- Industrial Analytics
- Problem Solving

---

## Final Reflection

Although the final model was not suitable for deployment due to limitations in the underlying data, the project provided valuable insights into industrial statistical modeling and reinforced a fundamental principle of analytics:

**Better algorithms cannot compensate for poor data quality.**

Understanding the process, validating assumptions, and questioning the data proved to be just as important as building the model itself.
