# E-Commerce Statistical Testing and Analysis

An end-to-end data science assignment utilizing programmatic statistical testing to analyze online retail transaction data and evaluate standard hypothesis tests.

## Overview
This project explores the relationship between e-commerce transaction attributes (such as quantity, unit price, and geography) and purchasing behavior. By applying practical Python-based statistical testing to large-scale data, this project demonstrates a structured approach to analyzing highly skewed financial datasets and validating fundamental statistical assumptions.

## Project Structure
- `ecommerce_statistical_analysis.ipynb`: Jupyter notebook containing the full data pipeline, EDA, and programmatic hypothesis tests.
- `data.csv`: The primary dataset used for the analysis. https://www.kaggle.com/datasets/carriel/ecommerce-data
- `Statistical Testing Report.pdf`: The final LaTeX-compiled academic summary of the findings.

## Key Phases
1. **Exploratory Data Analysis (EDA):** Performed data cleaning, feature engineering (`revenue`), and visualization (histograms, boxplots) to identify severe right-skewness and extreme outliers in e-commerce financial metrics.
2. **Statistical Testing (Python):** Implemented Shapiro-Wilk, Spearman rank correlation, Welch's two-sample t-test, One-Way ANOVA, and Chi-Square tests using `scipy.stats` to segment and analyze transactional behavior across different countries.

## Key Technologies
- **Python:** Data manipulation and programmatic testing.
- **SciPy/Pandas:** Statistical functions, hypothesis testing, and dataframe management.
- **Seaborn/Matplotlib:** Statistical data visualization.
- **LaTeX:** Academic report typesetting.

## Metrics & Findings
| Metric | Value |
| :--- | :--- |
| **Revenue Normality (Shapiro-Wilk p-value)** | < 0.0001 (Assumption Violated) |
| **Price vs. Qty Correlation (Spearman $r_s$)** | -0.4032 (Inverse Relationship) |
| **UK vs. Rest of World (t-statistic)** | -30.8258 |
| **Top Countries Variance (ANOVA F-Statistic)** | 10.2228 |
| **High-Value Independence (Chi-Square Stat)** | 358.1028 |

## Author
**Sepehr Barekati**
