# Health Insurance Charges — Statistical Analysis (R)

Statistical analysis project exploring factors influencing **health insurance charges** using a US insurance dataset (n=1338). The work includes descriptive statistics, hypothesis testing, correlation analysis, and multiple linear regression modelling.

## What’s in this repo
- `report/` — Final PDF report
- `src/` — R script used to perform the analysis

## Methods used
- Descriptive statistics + visualisations (histograms, boxplots, pie charts)
- Pearson correlation + correlation matrix
- Chi-square tests for categorical variables
- Multiple Linear Regression for charges prediction
- Charge split analysis (High vs Low) with t-tests and chi-square tests
- Kruskal–Wallis + post-hoc Dunn test for regional comparisons (BMI)

## How to run
1. Open `src/analysis.R` in RStudio
2. Ensure the dataset file name matches what the script expects (see script header)
3. Install packages if prompted (ggplot2, dplyr, corrplot, dunn.test)

## Notes
If the dataset is not included in this repo, download it from the original source and place it locally, then update the `read.csv()` path in the script.

