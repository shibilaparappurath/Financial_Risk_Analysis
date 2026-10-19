# Financial Risk Analysis & Customer Segmentation with Python

## Executive Overview
Developed as a training project, this repository delivers a comprehensive, data-driven financial risk analysis and customer segmentation model inspired by institutional banking workflows (such as those at Morgan Stanley). Using 800 transaction records across 189 unique accounts and 180 customers, the analysis evaluates cash-flow liquidity structures, balance volatility, anomaly detection, and statistical hypothesis testing to identify high-risk behavioral cohorts and formulate strategic business interventions.

> **Dataset Note:** *The dataset utilized in this project is a structured financial proxy dataset provided for case-study and portfolio evaluation purposes. It is designed to mirror retail and institutional banking structures to demonstrate technical proficiency in Python, exploratory data analysis, behavioral segmentation, and statistical modeling.*

## Key Analytical Tasks
* **Task 1 (Data Cleaning):** Standardized datetime fields, cleaned categorical features, and engineered guaranteed unique surrogate keys (`Unique_Tx_ID`).
* **Task 2 (Descriptive Analysis):** Established monthly transaction volume summaries, credit vs. debit cash-flow trends, and net inflow rankings.
* **Task 3 (Customer Profiling):** Implemented quartile-based activity rubrics (`High`, `Medium`, `Low`) and a 2x2 balance-volume segmentation matrix.
* **Task 4 (Financial Risk Identification):** Tracked overdraft exposure (`Min_Balance < 0`), quantified balance volatility via Coefficient of Variation (CV), and executed IQR and Z-score anomaly detection.
* **Task 5 (Data Visualization):** Generated executive visual suites (cash-flow distributions, segmentation matrices, volatility scatter plots, and correlation heatmaps) paired with detailed analytical commentary.
* **Task 6 (Hypothesis Testing):** Performed parametric (Welch's t-test, One-Way ANOVA) and non-parametric (Mann-Whitney U, Kruskal-Wallis H, Chi-Square) tests at a significance level of 0.05.
* **Task 7 (Strategic Recommendations):** Synthesized behavioral drivers into four data-backed interventions for real-time overdraft alerting, deposit-sweeping liquidity management, and product-agnostic risk monitoring.

## Repository Structure
* `data/`: Contains the raw proxy transaction dataset (`Morgan_Stanley.csv`).
* `notebooks/`: Contains the complete Jupyter Notebook (`Financial_Risk_Analysis.ipynb`).
* `requirements.txt`: Python package dependencies required to reproduce the analysis.
* `.gitignore`: Rules excluding temporary cache and checkpoint files from version control.

