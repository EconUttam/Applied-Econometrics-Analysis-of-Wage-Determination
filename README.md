# Applied Econometrics: Wage Determination & Time-Series Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EconUttam/Applied-Econometrics-Analysis-of-Wage-Determination/blob/main/Applied_Econometrics_Analysis_of_Wage_Determination.ipynb)

## 📌 Project Overview
This repository contains a comprehensive empirical econometric study investigating cross-sectional wage determination (`wage1`) and macroeconomic time-series dynamics (`phillips`). The analysis covers exploratory data audits, OLS regression modeling, functional form transformations, extensive diagnostic testing, and time-series specification evaluation.

## 📊 Key Highlights & Empirical Findings
- **Returns to Human Capital**: Baseline log-wage regressions indicate a statistically significant return to education of ~8.3% per additional year, alongside diminishing marginal returns to workforce experience and job tenure.
- **Gender Wage Gap & Interaction Effects**: Models incorporating dummy variables and interaction terms (`educ × female`) reveal structural wage differences across demographic groups and differential returns to education by gender.
- **Heteroskedasticity & Robust Inference**: Breusch–Pagan and White tests reject homoskedasticity in wage models. Heteroskedasticity-consistent (HC1) robust standard errors are applied to preserve valid inference.
- **Residual Normality**: Jarque–Bera diagnostics highlight moderate right-skewness in log-wage residuals.
- **Time-Series Serial Correlation**: Evaluation of the Phillips curve using Durbin–Watson and Breusch–Godfrey tests confirms significant $AR(1)$ autocorrelation, demonstrating the necessity of dynamic lag specifications.

## 📁 Repository Structure
```text
├── Applied_Econometrics_Analysis_of_Wage_Determination.ipynb  # Main Python analysis notebook
├── comprehensive_econometrics_project_report.pdf               # Full 50+ page written research report
├── applied_econometrics_executive_summary.pdf                  # 1-Page Executive Summary
├── README.md                                                   # Project documentation
└── .gitignore                                                  # Git ignore file
