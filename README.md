# 📊 Malaysia Assault Crime Analysis (2016–2023) — Data Science Mini Project  

This repository contains an exploratory data analysis (EDA) project examining **assault-related crimes in Malaysia** between **2016 and 2023**, using Python (pandas, matplotlib, seaborn).  
The analysis is based on publicly available data from **data.gov.my**.

---

## 🗂️ Project Files
| File | Description |
|------|-------------|
| `Crime.ipynb` | Full Jupyter Notebook containing data cleaning, analysis, visualizations and insights |
| `crime_district.csv` | Dataset used for analysis (district-level assault crime statistics) |

---

## 🎯 Project Objective  
To explore **patterns, trends, and insights** about assault crimes in Malaysia across districts and time, focusing on:  
- Annual assault crime trends  
- Comparison of crime rates across states and districts  
- Identification of high-risk locations  
- Observing any increasing/decreasing patterns  
- Basic visual analytics using Python  

---

## 🧼 Data Cleaning & Preparation  
Key preprocessing steps performed in the notebook:

- Removing missing or inconsistent entries  
- Renaming columns for clarity  
- Converting data types (e.g., year → int)  
- Grouping data by state, district, and year  
- Aggregating total crime counts  

---

## 📊 Exploratory Data Analysis (EDA)

The EDA focuses on answering several questions:

### 🔹 1. **Are assault crimes increasing or decreasing over the years?**  
Annual totals are plotted to observe national-level changes.

### 🔹 2. **Which states or districts report the highest assault cases?**  
Bar charts & sorted tables identify high-risk regions.

### 🔹 3. **What are the top contributing districts each year?**  
Helps highlight crime concentration areas.

### 🔹 4. **Distribution of assault cases across Malaysia**  
Basic comparisons using grouping and filtering.

### 🔹 5. **Any unusual spikes or drops?**  
Visualizations help spot anomalies.

---

## 📈 Visualizations Included

The notebook contains:  
- Line plots (yearly trends)  
- Bar charts (top states/districts)  
- Aggregated summaries  
- Tabular insights  

All generated using:  
```python
pandas
matplotlib.pyplot
seaborn
```

---

## 📥 Dataset Source

The dataset is originally sourced from data.gov.my under open data licensing.
It contains assault crime counts categorized by year, state, and district.

---

## 🚀 How to Run the Notebook
Install dependencies:
```bash
pip install pandas matplotlib seaborn jupyter
```

Run the notebook:
```bash
jupyter notebook Crime.ipynb
```

---

## 📌 Summary of Findings
- Assault crimes show fluctuating yearly trends, with several noticeable peaks.
- Certain states consistently record higher assault rates, possibly due to population density or urbanization.
- Some districts appear as recurring hotspots across multiple years.
- Visual analysis helps highlight states requiring focused preventive measures.

---
