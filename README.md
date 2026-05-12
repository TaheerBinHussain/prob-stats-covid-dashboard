# 🔬 COVID-19 Statistical Analysis Dashboard

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat-square)
![Dash](https://img.shields.io/badge/Dash-Plotly-informational?style=flat-square)
![Pandas](https://img.shields.io/badge/Data-Pandas-success?style=flat-square)
![SciPy](https://img.shields.io/badge/Stats-SciPy-orange?style=flat-square)
![Deployment](https://img.shields.io/badge/Deployed_on-Vercel-black?style=flat-square&logo=vercel)

A comprehensive, interactive web dashboard built to analyze global COVID-19 pandemic data. This application features a premium "glassmorphism" UI and performs real-time statistical modeling, distribution fitting, and regression analysis across 200+ countries. 

Developed as a semester project for **Probability & Statistics (Spring 2026)** at FAST-NUCES.

## ✨ Key Features

* **🌍 Global Overview:** Interactive choropleth maps and fatality scaling visualizations.
* **📈 Time Series Analysis:** 7-day rolling means and comparative progression metrics.
* **📋 Descriptive Statistics:** Automated calculation of means, standard deviations, quartiles, and 95% Confidence Intervals with visual box plots.
* **🎲 Probability Distributions:** Dynamic fitting of Normal and Log-Normal distributions. Includes Q-Q plots, normality tests, and an empirical vs. theoretical probability calculator.
* **🔗 Regression Modeling:** * **Simple Linear:** Visual scatter fitting with R², p-values, and 95% Prediction Intervals.
    * **Multiple Linear:** Key predictor analysis (GDP, life expectancy) against total fatalities.
* **📊 Country Comparison:** Normalized radar charts and grouped bar metrics for side-by-side analysis.

## 🗂️ Project Structure

* `code.py`: Main Dash application containing all UI and statistical logic.
* `covid_data.csv`: The primary dataset powering the dashboard.
* `requirements.txt`: Python dependencies required to run the app.
* `vercel.json`: Configuration file for Vercel serverless deployment.
* `report.pdf`: Comprehensive academic report detailing the statistical methodologies and findings of the project.

## 🚀 Local Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
