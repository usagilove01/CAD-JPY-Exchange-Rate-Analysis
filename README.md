# CAD/JPY Exchange Rate Analysis
Statistical analysis of CAD/JPY exchange rates and macroeconomic indicators using R.

## 1. Overview

This project examines the relationships between the CAD/JPY exchange rate and macroeconomic indicators in Canada and Japan from 2004 to 2023 using R.

## 2. Project Structure

| **File** | **Description** |
| --- | --- |
| [01 Data Preprocessing](cad_jpy_01_data_preprocessing.Rmd) | Data collection, cleaning, and integration |
| [02 EDA](cad_jpy_02_EDA.Rmd) | Exploratory data analysis and correlation analysis |
| [03 Regression Modeling](cad_jpy_03_regression_modeling.Rmd) | Linear regression, AIC comparison, and model diagnostics |
| [Processed Dataset](processed_data.csv) | Annual exchange rates and macroeconomic indicators |

# 3. Data
- **Yahoo Finance:** CAD/JPY exchange rates
- **World Bank (WDI):** GDP, inflation rates, and unemployment rates

The dataset contains 20 annual observations.

## 4. Key Findings

- Japan's GDP showed a strong negative correlation with CAD/JPY.
- Inflation rates in both countries were positively correlated with CAD/JPY.
- Canada's unemployment rate showed a negative correlation with CAD/JPY.
- The selected multiple regression model used Japan's GDP, inflation rate, and unemployment rate (**R² = 0.6923**).

## 5. Limitations

The small sample size and potential outliers limit the reliability of the results. The analysis identifies associations rather than causal relationships, and predictive performance was not evaluated on unseen data.

## 6. Tools and Technologies

R / R Markdown / tidyverse / ggplot2 / quantmod / WDI

## 7. How to Run

1. Install the required R packages.
2. Run `cad_jpy_01_data_preprocessing.Rmd` to generate `processed_data.csv`.
3. Run `cad_jpy_02_EDA.Rmd` and `cad_jpy_03_regression_modeling.Rmd`.



 
