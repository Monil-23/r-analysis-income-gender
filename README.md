# r-analysis-income-gender

# 📊 Income Inequality Analysis using NLSY97 (R Project)

This project investigates income inequality based on **sex-related differences** using data from the **National Longitudinal Survey of Youth 1997 (NLSY97)**. The analysis is performed using **R** and includes data preprocessing, exploratory analysis, hypothesis testing, and linear regression modeling.

---

## 📁 Files Included

- `Data_Analysis.Rmd` – R Markdown file with the full analysis
- `Data_Analysis.html` – Rendered output report

---

## 🧪 Central Research Question

> **Is there a significant difference in income between men and women?**
>
> Does the difference vary based on factors like education, marital status, childhood household, criminal record, or drug usage?

---

## 📊 What This Project Does

This project uses the **NLSY97 dataset** to explore whether there is a statistically significant difference in income between men and women, and how other factors may influence this gap. The analysis follows a structured data science workflow:

- 📥 **Data Cleaning & Preprocessing**
  - Load and rename variables for clarity
  - Filter out invalid or missing income values
  - Handle topcoded values (truncated top 2% of income)

- 📊 **Exploratory Data Analysis (EDA)**
  - Summarize data using mean, median, and proportions
  - Break down distributions by gender and other key factors like education, marital status, childhood background, and criminal history
  - Visualize patterns with histograms, boxplots, and bar charts

- 🧪 **Statistical Testing**
  - Perform hypothesis testing to compare income distributions between men and women
  - Calculate confidence intervals for income estimates
  - Assess normality assumptions before testing

- 📈 **Regression Modeling**
  - Build and interpret a multiple linear regression model using gender and other factors as predictors
  - Evaluate the model’s assumptions using residual plots and diagnostic checks
  - Interpret coefficients to understand the relative impact of each factor on income

- 📝 **Discussion & Conclusions**
  - Interpret key findings
  - Discuss limitations, such as topcoding and potential confounders
  - Reflect on the reliability of the analysis and its implications

---

## 📦 Tools Used

- **R / RStudio**
- **ggplot2**, **dplyr**, **readr**, **broom**, and base R
- R Markdown for documentation and report creation

---

## 📌 Key Findings

- A significant income gap exists between men and women.
- Factors such as education level and criminal history show clear correlation with income.
- Linear regression confirms that gender remains a strong predictor of income even after controlling for other variables.

---

## 📚 Dataset Source

- [Bureau of Labor Statistics – NLSY97](https://www.bls.gov/nls/nlsy97.htm)


---

