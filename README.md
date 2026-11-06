# H. pylori – S. boulardii RCT Analysis

## Project Overview
This repository contains the Python code used for the statistical analysis of a clinical trial evaluating the adjunctive use of Saccharomyces boulardii in Helicobacter pylori eradication therapy.

## Statistical Methods
The following statistical methods were used:
- **Normality assessment:** Shapiro–Wilk test.
- **Continuous variables:** Independent-samples t-test or Mann–Whitney U test, as appropriate.
- **Categorical variables:** Chi-square test or Fisher’s exact test, as appropriate.
- **Regression analysis:** Binary logistic regression using extended and reduced multivariable models.
- **Effect estimates:** Relative risk (RR) with 95% confidence intervals and adjusted odds ratios (aOR) with 95% confidence intervals.
- **Multiple comparisons:** False discovery rate (FDR) adjustment using the Benjamini–Hochberg procedure.
- **Data visualization:** Matplotlib.

## Repository Structure
- `clinical_trial_analysis.ipynb`: Jupyter Notebook containing the statistical analysis code.
- `synthetic_data.xlsx`: Synthetic dataset provided for demonstration and code testing.

## Requirements
The analysis uses the following Python libraries:
- pandas
- numpy
- scipy
- statsmodels
- matplotlib
- openpyxl
- IPython

## Synthetic Data
The original clinical trial dataset is not publicly available due to confidentiality considerations. A synthetic dataset is generated using Claude and provided to demonstrate the analytical workflow and facilitate code testing. It does **not** contain any real patient data. It **should not** be used for any scientific conclusion or secondary analysis.
