# Multiple Linear Regression"

# Prediction of Energy Consumption of Appliances 

This project explores the relationship between **Appliances Energy Consumption** and various **Temperature**  and **Environmental** variable factors.

---

## Objective

To predict energy consumption of appliances with various environmental and temperature factors.
---

## Dataset

## Interpretation

### Correlation:
- The correlation coefficient (**r > 0.80**) indicates a **strong positive relationship** between `Big Mac Price` and `New Hourly Wage`.

---

### OLS Regression Output:

| Metric               | Value               |
|----------------------|---------------------|
| R-squared            | 0.656               |
| Adjusted R-squared   | 0.643               |
| F-statistic          | 47.73               |
| Prob (F-statistic)   | 3.05e-07            |
| Observations         | 27                  |
| Durbin-Watson        | 2.153               |

---

### Model Equation:

> **New Hourly Wage = -4.4704 + 4.7029 × (Big Mac Price)**

- Intercept (-4.47): If the Big Mac price were $0 (hypothetically), the predicted wage would be -4.47 USD. While not realistic, it highlights the limits of extrapolating beyond the data range.
- Slope (4.70): For every $1 increase in Big Mac Price, the hourly wage is predicted to increase by approximately $4.70.

---

### Hypothesis Testing:

- **Null Hypothesis (H₀)**: Big Mac Price has no effect on New Hourly Wages.
- **p-value** for slope = 0.000 < 0.05 → Reject H₀  
 **Conclusion**: Big Mac Price **does** significantly affect New Hourly Wages. The model is statistically significant.

---

### Model Diagnostics:

- **Homoscedasticity**: Residuals have constant variance.
- **Linearity**: Relationship between predictors and response is linear.
