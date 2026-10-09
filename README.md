# premier-league-market-value-analysis
Premier League players' market value analysis using OLS regression and Python.
# Premier League Players' Market Value Estimation

### A Least Squares Regression Approach

## 📌 Project Overview

This project investigates the factors associated with Premier League football players' market values using Ordinary Least Squares (OLS) regression.

The analysis explores how age, playing time, and performance metrics such as Expected Goals (xG) and Expected Assists (xA) relate to player valuations.

The project was developed collaboratively as part of the MATH 2059 Linear Algebra course project assignment.

## 🎯 Objectives

- Analyze the relationship between player characteristics and market value.
- Compare multiple regression models to identify the best-fitting specification.
- Investigate the explanatory power of advanced performance metrics.
- Evaluate regression assumptions through residual diagnostics.

## 📊 Dataset

The dataset contains approximately 350 Premier League players and includes variables such as:

- Age
- Market Value
- Minutes Played
- Goals and Assists
- Expected Goals (xG)
- Expected Assists (xA)

The dependent variable, market value, was log-transformed to account for its right-skewed distribution.

## 🧮 Methodology

The project includes:

- Exploratory Data Analysis (EDA)
- Correlation Matrix
- Ordinary Least Squares (OLS) Regression
- Forward Selection and Model Comparison
- Quadratic Age Modeling (Age²)
- Residual Analysis
- Heteroskedasticity Testing
- Multicollinearity Analysis using VIF
- Outlier and Influence Analysis using Cook's Distance
- HC3 Robust Standard Errors

## 📈 Key Findings

The final selected model includes:

- Expected Goals (xG)
- Expected Assists (xA)
- Minutes Played
- Age
- Age²

The model achieved an adjusted R² of **0.505**, explaining approximately 50.5% of the variation in log market values in the analyzed sample.

The results suggest that advanced performance metrics, playing time, and the non-linear relationship between age and market value are useful for understanding player valuations.

## 🛠️ Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## 📁 Project Structure

- `market_value_analysis.ipynb` — Data analysis and regression modeling
- `PremierLeague_Merged_Project_Data.csv` — Dataset
- `project_report.docx` — Project report

## ⚠️ Limitations

The analysis is based on a limited sample of players. Market values may also be influenced by factors not included in the model, such as player position, defensive contributions, contract conditions, and market dynamics.

The findings describe statistical associations and should not be interpreted as proof of causation.

## 👥 Team Members

- Beyza Miyanyedi
- Emirhan Sevinç
- Muhammed Kadir Tunç
- Şeyma Babacan

## 🎓 Academic Context

MATH 2059 — Project Assignment

Submission Date: June 3, 2026
