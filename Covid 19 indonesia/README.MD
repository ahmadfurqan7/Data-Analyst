# 🦠 COVID-19 Indonesia: Data Analysis & Visualization

A data analysis portfolio project exploring the trajectory of the COVID-19 pandemic in Indonesia — from national growth trends down to province-level breakdowns of cases, deaths, and recoveries.

---

## 📌 Overview

This project uses the **`covid_19_indonesia_time_series_all.csv`** dataset to analyze how COVID-19 spread across Indonesia over time, and how its impact varied across provinces. The notebook combines data cleaning, aggregation, and rich visualizations (Matplotlib, Seaborn, and Plotly) to tell a clear, data-driven story of the pandemic in Indonesia.

📓 Notebook: [`analysis_covid19_indonesia.ipynb`](https://github.com/ahmadfurqan7/Data-Analyst/blob/main/Covid%2019%20indonesia/analysis_covid19_indonesia.ipynb)

---

## 🧹 Data Preparation

Before analysis, the raw dataset was inspected and cleaned:

- ✅ Checked and quantified **missing values** across all columns (count & percentage)
- ✅ Compared strategies for handling missing data — dropping rows, dropping columns, filling with `0`, and backward-filling
- ✅ Checked for **duplicate records**
- ✅ Explored **unique values** in key categorical columns (`Location ISO Code`, `Location`, `Province`, `Population`, `Population Density`)
- ✅ Converted the `Date` column to proper `datetime64` format for time-series analysis

---

## 📊 Analysis & Visualizations

### 🇮🇩 National Trends
- **Daily case growth** over time using an interactive Plotly line chart
- **Daily death trends** over time to track the pandemic's severity across different waves

### 🏙️ Province-Level Breakdown
Aggregated total cases, recoveries, and deaths per province, then calculated:
- **Death Percentage** per province
- **Recovery Percentage** per province

Visualized with horizontal bar charts to highlight:
- 📈 Provinces with the highest **total COVID-19 cases**
- ⚰️ Top 10 provinces by **total deaths**
- 📉 Top 10 provinces by **death percentage**
- 💚 Top 10 provinces by **total recoveries**

---

## 💡 Key Findings

- 📅 The **highest single-day case count** in Indonesia was recorded on **July 9, 2020**, with **5,268 new cases**.
- ⚰️ The **highest single-day death count** occurred on **July 22, 2020**, with **273 deaths**.
- 🏆 **East Java** recorded the **highest total number of COVID-19 cases and deaths** among all provinces.
- 💚 East Java was also the province with the **highest number of recoveries** — reflecting both the scale of its outbreak and its healthcare response.

> *Data analyzed covers the period from March 1, 2020 to September 16, 2022.*

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** & **NumPy** — data cleaning & manipulation
- **Matplotlib** & **Seaborn** — static visualizations
- **Plotly Express** — interactive time-series charts
- **Jupyter Notebook** — analysis environment

---

## 🎯 What This Project Demonstrates

- Practical **data cleaning** techniques for handling missing and inconsistent real-world data
- **Time-series analysis** of pandemic trends using `groupby()` and datetime operations
- Multi-library **data visualization** skills (static + interactive charts)
- Ability to derive and communicate **clear, actionable insights** from public health data

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
