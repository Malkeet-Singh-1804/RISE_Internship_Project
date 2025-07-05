# RISE_Internship_Project
Project File

# 🦠 COVID-19 Data Analysis Project

## 📌 Problem Statement

Understanding COVID-19 trends is essential for designing and implementing effective public health policies. By analyzing confirmed, recovered, and death data globally, we can uncover how the virus spread over time and how different regions responded.

---

## 🎯 Objective

Analyze global COVID-19 data to:

* Visualize the **growth of cases**
* Track **recoveries and deaths**
* **Compare countries** based on COVID-19 metrics
* Present a **visual story** of the pandemic using plots and charts

---

## 🗂 Dataset

* File: `covid_19_clean_complete.csv`
* Source: Kaggle or public COVID-19 dataset
* Features:

  * `Date`: Reporting date
  * `Country/Region`: Country name
  * `Province/State`: Sub-region (if available)
  * `Confirmed`, `Recovered`, `Deaths`: Daily cumulative numbers
  * `Lat`, `Long`: Geolocation
  * `Active`: Active cases (computed)
  * `WHO Region`: World Health Organization region

---

## 🔧 Requirements

```bash
pip install pandas matplotlib seaborn
```

---

## 🔍 Steps Performed

### ✅ 1. Data Preprocessing

* Converted `Date` to datetime format
* Handled missing values in `Province/State`
* Aggregated daily data for global trends

### ✅ 2. Global Trend Analysis

* Cumulative line plots for:

  * Confirmed cases
  * Recoveries
  * Deaths

### ✅ 3. Area Chart

* Stacked area chart showing cumulative COVID-19 cases over time

### ✅ 4. Country Comparison

* Identified top 5 countries by confirmed cases
* Line chart showing how the pandemic evolved in those countries

### ✅ 5. Heatmap of Deaths

* Focused on top 10 countries by total deaths
* Heatmap of death trends over time

---

## 📊 Visualizations Included

| Visualization               | Description                                       |
| --------------------------- | ------------------------------------------------- |
| 📈 Line Plot                | Global confirmed, recovered, and death trends     |
| 🌈 Area Chart               | Stacked visual of total pandemic impact           |
| 🌍 Country Comparison Chart | Top 5 countries' confirmed case growth            |
| 🔥 Heatmap                  | Daily death trends for top 10 worst-hit countries |

---

## 🧠 Key Insights

* The pandemic followed an exponential growth pattern early on.
* Recovery rates improved globally, although death tolls steadily increased.
* Different countries faced different waves of the pandemic at different times.
* Heatmaps revealed when each country experienced peak mortality.

---

## 📁 Folder Structure

```
📦 COVID-19-Analysis/
├── covid_19_clean_complete.csv
├── covid_analysis.ipynb
├── plots/
│   ├── global_line_plot.png
│   ├── area_chart.png
│   ├── country_comparison.png
│   └── deaths_heatmap.png
└── README.md
```

---

Future Scope

* Integrate vaccination data to analyze effects on case/death trends.
* Build a dashboard using Streamlit or Power BI.
* Predict future case trends using Time Series models (e.g., ARIMA, Prophet).

Malkeet Singh
MCA Student
