# gold-usd-time-series-analysis
Time-series and econometric analysis of the relationship between Gold Prices and the US Dollar Index using Python.

**Project Overview**

This project analyzes the relationship between gold prices and the US Dollar Index using financial time-series analysis and econometric methods.

Gold is often considered a safe-haven asset, and its price movements are frequently associated with fluctuations in the US Dollar.

The objective of this project is to explore the statistical and dynamic relationship between these two variables using various econometric techniques.

**Research Questions**

This project investigates the following questions:

1.Is there a correlation between gold prices and the US Dollar?
2.Does the US Dollar influence gold price movements?
3.Do lagged USD values help predict gold returns?
4.Is there evidence of Granger causality between the variables?
5.How do shocks in the USD affect gold prices over time?

**Dataset**

The dataset contains monthly observations of:

Variable	Description
Date	Monthly observation date
Price	Gold price (USD per ounce)
Exchange rate	US Dollar Index

Data sources include:

- Federal Reserve Economic Data (FRED)
- Historical gold price datasets

The data was cleaned and merged to ensure consistent monthly frequency.

**Tools and Technologies**

This project was implemented using the following tools:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels

These libraries were used for data cleaning, visualization, and econometric modeling.

**Methodology**

The analysis was conducted in several stages:

Data Cleaning
- Removing formatting issues
- Converting values to numeric
- Handling missing values
- Aligning time series
Exploratory Data Analysis
- Trend visualization
- Correlation analysis
- Rolling correlation analysis
Econometric Modeling
- Ordinary Least Squares (OLS) regression
- Lag correlation analysis
- Granger causality testing
- Vector Autoregression (VAR)
Dynamic Analysis
- Impulse Response Functions
- Key Visualizations

Examples of visualizations included in the analysis:

- Gold price time series
- USD index time series
- Rolling correlation between gold and USD
- Lag correlation analysis
- Impulse response functions

**Results**

Preliminary analysis suggests that:

- Gold prices and the US Dollar exhibit a negative relationship
- The relationship varies over time
- Lagged USD values may provide predictive information for gold returns
Further econometric analysis is used to explore these dynamics.
