# 🦠 COVID-19 Clinical Trials Dashboard

## 📊 Project Overview

This project presents a complete Exploratory Data Analysis (EDA) of global COVID-19 clinical trials using Python and Pandas in Google Colab. The dataset, sourced from ClinicalTrials.gov, contains detailed records of clinical studies conducted worldwide. The project includes data cleaning, missing value handling, categorical processing, and visual exploration to derive valuable insights.

---

## 🧩 Problem Statement

The aim of this project is to analyze COVID-19 clinical trials data to:
- Understand trial distribution across gender, phases, and status
- Identify leading sponsoring organizations and countries
- Handle complex missing data with proper imputation
- Discover trends in trial enrollments and start dates
- Build visual dashboards that summarize the landscape of global COVID research

---

## 📁 Dataset Description

- **Source**: [ClinicalTrials.gov](https://drive.google.com/file/d/1WessMr8tdADxk04uVT-AaoP3_CxwJIYR/view)
- **Records**: 5,783 clinical trials
- **Features**: 25+ columns including:
  - `NCT Number`, `Title`, `Status`, `Phases`, `Enrollment`
  - `Study Type`, `Gender`, `Start Date`, `Sponsor/Collaborators`, `Conditions`, etc.

---

## 🛠️ Steps Followed

- ✅ **Data Import**: Loaded dataset using Pandas in Google Colab  
- 🧹 **Data Cleaning**: Removed duplicates, dropped high-null columns  
- 🧠 **Missing Value Handling**:  
  - Categorical features → imputed using `"Missing <Feature>"`  
  - Numerical (`Enrollment`) → imputed using `median`  
- 🏷️ **Feature Engineering**: Extracted country from location, start year from dates  
- 📊 **Visualizations**: Created using Seaborn and Matplotlib  
- 🔍 **EDA Analysis**: Distribution plots, crosstabs, country-wise breakdowns

---

## 📸 Dashboard Preview

> *Plots were generated using Python and displayed inline in Colab. Examples include:*
- Bar chart of trial status  
- Top 10 contributing countries  
- Gender-wise trial distribution  
- Monthly trial start trend  

---

## 💡 Key Insights

- Majority of trials were conducted in the **United States**, **France**, and **UK**
- Over 40% of trials were in **Phase 2 or 3**
- **Median enrollment** was much lower than the mean due to extreme outliers
- A significant number of trials do not have results publicly posted
- Many fields had **missing values**, but most could be reasonably imputed

---

## ✅ Recommendations

1. **Focus Analysis on Countries with Rich Data**  
   Avoid conclusions from countries with sparse or poor-quality data.

2. **Visual Imputation Audits**  
   Use plots to verify post-imputation distributions.

3. **Improve Reporting Standards**  
   Encourage researchers to publish study results for transparency.

4. **Study Enrollment Patterns**  
   Further explore factors leading to high vs. low enrollment trials.

5. **Prepare for ML Models**  
   Dataset can now be used for modeling (e.g., predicting trial status or success) after encoding.

---

## 📁 Files Included

- `COVID clinical trials.csv` – Original dataset  
- `covid_19_clinical_trails_dashboard.py` – Python script from Google Colab  
- `COVID-19 Clinical Trials EDA Pandas.pdf` – Project reference guide  
- `README.md` – Project documentation  

---

## 🙋‍♂️ About Me

I'm a data analyst with experience in **Pandas**, **Python**, and **data visualization**, passionate about healthcare data projects.  
Check out more on my [GitHub Profile](https://github.com/Sathwik-pabba).

---

## 🔗 Connect with Me

- 💼 [LinkedIn](https://linkedin.com/in/sathwikpabba)
- 📫 Email: sathwik.pabba18@email.com
