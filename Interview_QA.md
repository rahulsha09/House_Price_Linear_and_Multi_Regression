# Linear Regression Interview Questions & Answers

**1. What assumptions does linear regression make?**
- Linearity: Relationship between input variables and output is linear.
- Independence: Observations are independent.
- Homoscedasticity: Constant variance of residuals/errors.
- Normality: Residuals (errors) are normally distributed.
- No/low multicollinearity: Independent variables aren't highly correlated.


**2. How do you interpret the coefficients?**
- Each coefficient represents the expected change in the target (house price) for a one-unit increase in that feature, keeping other variables constant.
- Positive value: Feature increases price; Negative: decreases price.


**3. What is R² score and its significance?**
- The R² value indicates the proportion of target variance explained by the model.
- R² = 0.8 means 80% of the variation in house prices is explained by the features in your model.


**4. When would you prefer MSE over MAE?**
- Use MSE when **large errors should be penalized more** (outlier sensitivity), e.g., finance.
- Use MAE when you want a **robust, average sense of error** without outlier amplification.


**5. How do you detect multicollinearity?**
- High correlation between predictors (correlation > 0.8).
- High VIF (Variance Inflation Factor): VIF > 5/10 signals multicollinearity.
- Unstable/regression coefficients.


**6. Simple vs. Multiple Regression?**
- Simple regression: One input variable, one output/prediction (Y = a + bX).
- Multiple regression: Multiple features as inputs (Y = a + b1X1 + b2X2 + ...).


**7. Can linear regression be used for classification?**
- No, linear regression is for continuous outputs. Regression can't naturally model binary or categorical target variables.


**8. What happens if you violate regression assumptions?**
- Coefficient values may become biased or misleading.
- Standard errors, t-values, model reliability, and predictions might be incorrect.


**What is VIF?**
- Variance Inflation Factor quantifies how much the variance of a regression coefficient is inflated due to multicollinearity.

**End.**

