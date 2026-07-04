# Credit Delinquency Risk Analysis

This repository contains an interpretable credit-risk modeling project using
logistic regression on delinquency and credit behavior variables.

## Project Summary

The analysis predicts serious delinquency within two years and emphasizes
statistical interpretability rather than black-box prediction.

Main components:

- missing-value handling for income and dependents
- logical cleaning for impossible ages and delinquency special codes
- outlier and inconsistency checks
- log transformation and robust feature engineering
- multicollinearity diagnostics with VIF
- BIC-driven logistic regression model selection
- coefficient and odds-ratio interpretation
- bootstrap confidence intervals
- credit-policy recommendations based on model results

## Repository Layout

```text
notebooks/
  credit_delinquency_logistic_regression.ipynb
figures/
  1_vif_hunch_heatmap.png
  2_distribution_hunch_plots.png
  3_nonlinearity_hunch_plot.png
```

## Data Policy

Original and cleaned CSV files are not included in this public snapshot. The
source folder contained course/project data files, so this repository keeps the
analysis notebook and selected result figures only.

To rerun the analysis, place a compatible credit-risk training CSV under a local
`data/` directory and update the notebook path as needed.

## Notes

The project is designed as a portfolio artifact for explainable statistical
modeling: it focuses on why variables are transformed or removed, how model
terms are interpreted, and how uncertainty is communicated.
