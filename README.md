# 🏠 American House Prices: Multiple Linear Regression Analysis

## Overview

This project explores the relationship between key housing features and home prices in major U.S. cities using **Multiple Linear Regression (MLR)**. We use a rich dataset from Kaggle that includes real estate listings along with demographic details.

## Dataset

**Source:** [Kaggle - American House Prices](https://www.kaggle.com/datasets/jeremylarcher/american-house-prices-and-demographics-of-top-cities/data)  
**File used:** `American_Housing_Data_20231209.csv`

## Objective

- Identify how `beds`, `baths`, and `living_space` affect `price`
- Perform linear regression modeling with diagnostic checks
- Evaluate and correct assumption violations through transformations and feature engineering

## Key Techniques

- **OLS Regression using `statsmodels`**
- **Exploratory Data Analysis (EDA)** with `seaborn` and `matplotlib`
- **Multicollinearity check** via Variance Inflation Factor (VIF)
- **Log transformations** and **categorical binning**
- **Interaction effects** between continuous variables
- **Winsorization** to address outliers
- **Regression diagnostics**: residual plots, Q-Q plots, and Breusch-Pagan test for heteroscedasticity

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy

## Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/american-house-prices-regression.git
   cd american-house-prices-regression
