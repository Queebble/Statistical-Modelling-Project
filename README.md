
# Rainfall & SOI Regression Analysis

This project investigates the relationship between the **Southern Oscillation Index (SOI)** and **seasonal rainfall** across Australia. 
It employs linear regression and exploratory data analysis techniques to assess the impact of SOI on precipitation patterns.

## 📊 Project Goals
- Merge and clean seasonal rainfall and SOI datasets
- Visualise rainfall trends across seasons
- Build and evaluate linear and polynomial regression models
- Perform residual diagnostics and model refinement

## 🛠️ Tools & Libraries
- R
- tidyverse
- ggplot2
- broom

## 📈 Visual Outputs
- Faceted scatter plots of SOI vs rainfall by season
- Regression lines with null model comparison
- Residual plots and Q-Q plot for diagnostics

## 📁 Files
- `Statistical-Modelling-Project.Rmd`: Cleaned and annotated R Markdown report
- CSV files: `seasonal_soi_data.csv`, `total_seasonal_rainfall.csv`

## 🧠 Key Insights
- A moderate positive relationship exists between SOI and rainfall in **Summer**
- Other seasons show weaker or negligible trends
- A polynomial model marginally improves fit over a basic linear model

## 🔄 Reproducibility
To run this project:
1. Clone the repository
2. Open the `.Rmd` file in RStudio
3. Knit to HTML or PDF

---

Created as part of a data science coursework project, demonstrating regression modelling, EDA, and statistical communication.
