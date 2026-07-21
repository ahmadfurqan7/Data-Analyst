# 🧹📊 Data Cleaning & Exploratory Data Analysis with Pandas

A hands-on portfolio project demonstrating core data wrangling and exploratory data analysis (EDA) skills using **Python** and **Pandas** — from raw, messy data to clean datasets and meaningful visual insights.

---

## 📌 Overview

This repository contains two Jupyter notebooks that showcase two essential stages of a data analyst's workflow:

| Notebook | Focus | Dataset |
|---|---|---|
| [`Data_Cleaning.ipynb`](https://github.com/ahmadfurqan7/Data-Analyst/blob/main/EDA%20Pandas/Data%20Cleaning.ipynb) | Cleaning a messy customer contact list | `Customer Call List.xlsx` |
| [`EDA_In_Pandas.ipynb`](https://github.com/ahmadfurqan7/Data-Analyst/blob/main/EDA%20Pandas/EDA%20In%20Pandas.ipynb) | Exploring global population trends | `world_population.csv` |

Together, they walk through the full journey of turning raw, inconsistent data into something clean, structured, and ready for analysis — then extracting real insights from it.

---

## 🧹 Part 1: Data Cleaning

**Goal:** Transform a messy customer call list into a clean, analysis-ready dataset.

### Key techniques applied
- ✅ Removing duplicate rows with `drop_duplicates()`
- ✅ Dropping irrelevant/unused columns
- ✅ Stripping inconsistent characters (`.`, `_`, `/`, digits) from names using `str.strip()`
- ✅ Cleaning and standardizing phone numbers with regex (`str.replace`) and reformatting into a consistent `XXX-XXX-XXXX` pattern
- ✅ Splitting a single "Address" column into `Street_Address`, `State`, and `Zip_Code`
- ✅ Standardizing categorical values (`Yes`/`No` → `Y`/`N`)
- ✅ Handling missing/placeholder values (`N/a`, `NaN`) with `fillna()`
- ✅ Filtering out rows based on business logic (e.g., customers who opted out, or have no phone number)
- ✅ Resetting the index for a clean final dataset

### Why it matters
Real-world data is rarely analysis-ready. This notebook demonstrates a practical, step-by-step approach to identifying and fixing common data quality issues — a critical skill for any data analyst or data scientist.

---

## 📊 Part 2: Exploratory Data Analysis (EDA)

**Goal:** Explore a world population dataset to uncover trends, relationships, and outliers across continents and decades.

### Key techniques applied
- 🔍 Dataset inspection with `.info()`, `.describe()`, `.isnull().sum()`, `.nunique()`, and `.dtypes`
- 🔍 Filtering numeric vs. categorical columns with `select_dtypes()`
- 🔍 Ranking countries by population (`sort_values()`)
- 🔍 Correlation analysis with `.corr()` and a **Seaborn heatmap**
- 🔍 Aggregating data by continent using `groupby()`
- 🔍 Tracking population growth from **1970 to 2022** across continents with line plots
- 🔍 Detecting spread and outliers using **boxplots**

### 💡 Key Insights
- **Asia** has been the most populous continent since 1970, and its population has continued to grow through 2022 — while **Oceania** has consistently remained the least populous.
- Population scale across continents follows the order: **Asia >> South America > Africa > Europe ≈ North America > Oceania**.
- **Asia and Africa** show the greatest population diversity among their countries, while **Europe and Oceania** are the most uniform.
- One clear **outlier** was identified in Europe — a country whose population deviates significantly from the rest of the continent.

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** — data manipulation & cleaning
- **Seaborn** & **Matplotlib** — data visualization
- **Jupyter Notebook** — interactive analysis environment

---

## 🎯 What This Project Demonstrates

- Strong understanding of **data cleaning fundamentals** (deduplication, string manipulation, regex, handling missing data)
- Practical **EDA workflow**, from summary statistics to visual storytelling
- Ability to translate raw numbers into **clear, actionable insights**
- Comfort working with **Pandas, Seaborn, and Matplotlib** in a real analytical context

---

## 📬 Contact

Feel free to reach out if you have questions, feedback, or just want to connect!

⭐ If you found this project useful or interesting, consider giving it a star!

---

## License

This project is licensed under the MIT [LICENSE](LICENSE) use it freely for learning, teaching, or building.
```
  _    _ _  ______  _   _ 
 | |  | | |/ / __ \| \ | |
 | |  | | ' / |  | |  \| |
 | |  | |  <| |  | | . ` |
 | |__| | . \ |__| | |\  |
  \____/|_|\_\____/|_| \_|                
```

