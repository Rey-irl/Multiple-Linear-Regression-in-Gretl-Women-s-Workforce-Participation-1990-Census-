## Project Information
- **Title**: Multiple-Linear-Regression-in-Gretl-Women-s-Workforce-Participation-1990-Census
- **Author**: Reyna Vargas
- **Date of Creation**: June 11, 2016

This study develops a Multiple Linear Regression model using data obtained from Gretl, focusing on the percentage of women aged 16 and older engaged in manual labor, based on 1990 Census data compiled by Luis Cruz. The objective is to identify key socioeconomic and demographic factors influencing women’s participation in manual labor.

The regression model initially incorporated various explanatory variables, including female and male median income, education level, unemployment rate, marital status, urban residency, and race. After evaluating statistical significance and model fit, variables such as male income and marital status were excluded to improve the model.

The final model highlights that the most influential factors positively associated with women’s participation in manual labor are:

-Female median income (YF)
-Secondary education completion (EDUC)
-Divorced status (DR)

Meanwhile, factors like unemployment rate (UE), urban residency (URB), and being white (WH) had a negative but statistically significant influence.

Statistical diagnostics, including tests for **linearity, normality, heteroscedasticity, and collinearity**, were applied. The model showed strong explanatory power with an adjusted R² of 74.6%, and after correcting for heteroscedasticity, the adjusted R² improved to 89.2%, indicating a robust fit.

## 🧾 Model Summary

Final Regression Equation:
ŵlfp = 49.9443 + 0.8176yf + 0.2797educ - 1.7753ue - 0.0680urb - 0.1971*wh

- **Dependent Variable**: WLFP (Percentage of women in manual labor)
- **Adjusted R²**: 89.2%
- **Tool Used**: Gretl

The analysis concludes that education and economic necessity are key drivers for women's involvement in manual labor. Additionally, being divorced or having limited income may push women toward these roles, particularly when other opportunities are restricted due to lower education or social conditions.

## 📁 Contents

- `Proyecto_Regresion_Lineal_Reyna Vargas.pdf` – Full report in Spanish

## 📚 References

1. [Gretl User Guide](http://gretl.sourceforge.net/)
2. [Census Data (1990), USA]
3. Relevant econometric texts on MLR, OLS estimation, and diagnostic testing

