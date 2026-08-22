# Data Analytics Portfolio

A collection of data analytics tasks completed during my Data Analytics Internship at Progree (July–August 2026), working with the [UCI Online Retail dataset](https://archive.ics.uci.edu/dataset/352/online+retail) — a real transactional dataset from a UK-based online gift retailer (Dec 2010–Dec 2011).

## Contents

### 📁 eda-cleaning
Exploratory data analysis and data cleaning on the raw transactional dataset — handling missing values, duplicates, and outliers using pandas, numpy, and missingno.

### 📁 rfm-segmentation
Customer segmentation using the RFM (Recency, Frequency, Monetary) framework, with an interactive dashboard built in Tableau Public.
- 🔗 [View live dashboard on Tableau Public](https://public.tableau.com/app/profile/rimsha.shahzad/viz/OnlineRetailCustomerSegmentation_17863539917990/CustomerSegmentationDashboard)
- Includes exported PDF versions of the dashboard (standard and filtered views)

### 📁 hypothesis-testing-and-sarima-forecast
Two analyses in one notebook:
- **Hypothesis testing** — comparing order values across countries using ANOVA (F = 5.5591, p = 0.0002) and Kruskal-Wallis (H = 248.97, p < 0.0001), plus a Chi-Square test of association
- **SARIMA forecasting** — modeling weekly-seasonal daily revenue, validated with an Augmented Dickey-Fuller stationarity test, achieving MAE ≈ 18,475 and RMSE ≈ 29,787 on the held-out test period

## Tools & Libraries
Python (pandas, numpy, matplotlib, seaborn, missingno, scipy.stats, statsmodels), Google Colab, Tableau Public

## Dataset
[UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail) — Chen, D. (2015), UCI Machine Learning Repository, licensed under CC BY 4.0.
