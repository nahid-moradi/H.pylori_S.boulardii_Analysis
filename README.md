# hpylori_sboulardii_rct_analysis
# H. pylori – S. boulardii RCT Analysis

## Project Overview
This repository contains the Python code used for the statistical analysis of a clinical trial evaluating the adjunctive use of Saccharomyces boulardii in Helicobacter pylori eradication therapy.

## Statistical Methods
The following statistical methods were used:
- **Normality assessment:** Shapiro–Wilk test.
- **Continuous variables:** Independent-samples t-test or Mann–Whitney U test, as appropriate.
- **Categorical variables:** Chi-square test or Fisher’s exact test, as appropriate.
- **Effect estimates:** Relative risk (RR) with 95% confidence intervals.
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

## Data Availability
The original clinical trial dataset is not publicly available due to confidentiality considerations. A synthetic dataset is provided to demonstrate the analytical workflow and facilitate code testing.

## Disclaimer
The synthetic dataset consists entirely of fabricated data and does not represent actual trial participants or clinical observations. Results generated using this dataset are for demonstration purposes only and do not reproduce the findings of the original clinical trial.
