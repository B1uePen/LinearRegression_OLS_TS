# LinearRegression_OLS_TS
Linear Regression Analysis with OLS and Theil-Sen Estimator

This project demonstrates **linear regression analysis** using both Ordinary Least Squares (OLS) and the robust **Theil-Sen estimator**, including residual analysis, confidence intervals, and the impact of outliers.

The goal of this project is to simulate data, fit a linear regression model, and evaluate its quality. It also explores how the presence of an outlier affects standard OLS regression and compares it with the robust Theil-Sen method.


**Key steps performed:**

1. **Data Generation**  
   - Created synthetic dataset with `X` from a uniform distribution and `Y` from a linear relationship plus normal noise.  
   - Added a strong outlier to assess model robustness.

2. **Linear Regression (OLS)**  
   - Estimated parameters `a_hat` (intercept) and `b_hat` (slope).  
   - Plotted data points and regression line.  
   - Calculated model quality metrics:
     - R-squared
     - t-tests for parameter significance
     - F-test for model adequacy

3. **Residual Analysis**  
   - Computed residuals and standardized residuals.  
   - Plotted:
     - Residuals vs predicted values
     - Residuals vs X
     - Histogram of residuals
     - Q-Q plot for normality check

4. **Confidence Intervals**  
   - Constructed 95% confidence intervals for:
     - New observation prediction
     - Regression line estimate

5. **Outlier Handling & Robust Regression**  
   - Added an outlier to the dataset.  
   - Re-calculated OLS parameters and compared with Theil-Sen estimator.  
   - Theil-Sen estimator demonstrated higher robustness to the outlier.

6. **Results Comparison**  
   - Computed relative errors for both methods.  
   - Summarized in a table showing that Theil-Sen is less affected by outliers.

---

## Technologies Used

- Python 3  
- NumPy (data generation, calculations)  
- Pandas (data tables and display)  
- Matplotlib (plots and visualization)  
- SciPy (statistical tests and Theil-Sen estimator)
