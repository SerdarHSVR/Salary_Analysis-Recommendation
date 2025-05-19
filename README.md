# 💼 Salary Analysis & Recommendation Report

**Author:** Serdar Hoşver  
**Course:** ADS 575 – Applied Testing in Data Science  
**University:** TED University | Applied Data Science  
**Project Topic:** Salary Determinants, Equity Evaluation & Recommendation  
**Company Analyzed:** Monsanto (Acquired by Bayer)

---

## 📌 Project Description

This project focuses on the **exploratory and statistical analysis** of employee salaries within Monsanto, a company now owned by Bayer. The goal is to understand key factors influencing salary differences, identify any potential bias (e.g., based on gender or marital status), and generate data-driven recommendations for equitable compensation strategies.

---

## 📊 Dataset

- **File:** `employees_data.csv`
- **Total Observations:** 400+
- **Features Include:**
  - Demographics (age, gender, marital status, education)
  - Organizational roles (department, profession, seniority)
  - Behavioral flags (working while studying)
  - Salary values (target variable)

---

## 🧪 Methodology

The analysis followed these steps:

1. **Data Cleaning & Preprocessing**
   - Renaming columns
   - Handling missing values
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Group-wise salary averages by gender & marital status
   - Salary distributions across departments and professions
   - Boxplots and group comparisons

3. **Statistical Testing**
   - Independent t-tests (e.g., gender-based salary differences)
   - ANOVA (department-wise salary analysis)
   - ANCOVA (adjusting for covariates)

4. **Regression Analysis**
   - Linear regression model with one-hot encoded variables
   - OLS summary interpretation
   - Assessment of model significance and multicollinearity

5. **Recommendations**
   - Data-driven HR suggestions for salary review and adjustment
   - Department-level interventions
   - Long-term monitoring strategy

---

## 📌 Key Findings

- Significant salary differences were observed across departments and professions.
- Gender and marital status had interaction effects on pay distribution.
- Regression analysis revealed strong predictors including seniority and department.
- Several outliers and potential salary disparities were flagged for HR review.

---


---

## 🧠 Skills Applied

- Pandas & NumPy for data wrangling
- Matplotlib & Seaborn for visualization
- Statsmodels & Scipy for hypothesis testing and modeling
- Regression interpretation & policy recommendation

---

## 📝 License

This project is created for academic purposes as part of the ADS575 course at TED University. Please credit the author if referencing this work.

---




