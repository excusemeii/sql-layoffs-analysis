# 🚀 SQL Project: Data Cleaning & Exploratory Data Analysis (EDA) on Global Layoffs  

![SQL Badge](https://img.shields.io/badge/SQL-Data--Cleaning-blue) ![EDA Badge](https://img.shields.io/badge/EDA-Exploratory--Analysis-orange) ![Kaggle Badge](https://img.shields.io/badge/Dataset-Kaggle-green)  

## 📌 Project Overview  
This project focuses on **real-world data cleaning and exploratory data analysis (EDA)** using SQL.  
The dataset, sourced from [Kaggle – Layoffs 2022](https://www.kaggle.com/datasets/swaptr/layoffs-2022), captures global layoff trends across industries, companies, and geographies.  

The goal of this project was to:  
- Build a **clean, reliable dataset** by handling duplicates, nulls, inconsistent formats, and irregular values.  
- Perform **EDA in SQL** to uncover patterns and insights around layoffs by company, industry, country, and time period.  
- Demonstrate strong **SQL skills** in data cleaning, transformation, and analytical query writing.  

---

## ⚡ Key SQL Skills Demonstrated  
- ✅ Creating staging tables for raw & clean data separation  
- ✅ Removing duplicates using **window functions (ROW_NUMBER, DENSE_RANK)**  
- ✅ Handling missing data & standardizing inconsistent entries  
- ✅ String transformations & data type conversions (`STR_TO_DATE`, `TRIM`, `CAST`, `NULLIF`)  
- ✅ Exploratory analysis using **aggregations, GROUP BY, CTEs, and window functions**  
- ✅ Rolling totals and trend analysis with **window functions**  

---

## 🛠️ Data Cleaning Steps  
1. **Remove duplicates** → Identified using `ROW_NUMBER()` and deleted safely.  
2. **Standardize data** → Fixed industry names (e.g., *CryptoCurrency → Crypto*), corrected inconsistent country names (e.g., *United States.* → *United States*).  
3. **Handle nulls & blanks** → Updated blank industries by inferring from other rows of the same company.  
4. **Fix data types** → Converted text dates into proper `DATE` format.  
5. **Remove unusable rows** → Deleted records with no meaningful values for layoffs.  

---

## 📊 Exploratory Data Analysis (EDA) Queries  
Some of the analyses performed:  
- 🔹 **Biggest single layoffs** and companies with the most total layoffs.  
- 🔹 **Industry-level trends**: Which industries were hit hardest?  
- 🔹 **Country-wise layoffs**: Which countries saw the most job cuts?  
- 🔹 **Yearly analysis**: Layoff trends over 2020–2023.  
- 🔹 **Rolling monthly layoffs** using window functions.  
- 🔹 **Top 3 companies per year** ranked by layoffs.  

---

## 📈 Example Insights  
- Tech startups and crypto-related companies show a **higher concentration of 100% layoffs**.  
- The **United States** dominates layoff counts, followed by other regions.  
- Layoffs peaked around **2023–2024**, aligning with global macroeconomic shifts.  

---
## 🤝 Let’s Connect  
👩‍💻 **Author:** Kanchan Joshi  
🔗 [LinkedIn](https://www.linkedin.com/in/kanchan101/) | 📧 joshikn@mail.uc.edu
