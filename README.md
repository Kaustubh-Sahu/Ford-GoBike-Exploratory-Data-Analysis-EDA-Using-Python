# 🚲 Ford GoBike Exploratory Data Analysis (EDA) Using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## 📌 Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on the **Ford GoBike bike-sharing dataset** using Python. The analysis focuses on understanding rider behavior, trip patterns, station utilization, and seasonal demand by processing over **2 million trip records**.

Through data cleaning, feature engineering, and visual analytics, the project uncovers meaningful insights that can help optimize bike availability, improve operational efficiency, and support data-driven business decisions.

---

## 🎯 Business Objectives

- Analyze rider demographics and user types.
- Identify ride demand across months, weekdays, and hours.
- Study ride duration patterns.
- Discover the busiest start and end stations.
- Explore relationships between different variables.
- Generate actionable business insights and recommendations.

---

## 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | Ford GoBike Trip Data |
| Domain | Bike Sharing / Transportation |
| Records | 2+ Million |
| Variables | 16+ |
| Format | CSV |
| Time Period | One Year |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```text
Ford-GoBike-EDA/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── Ford_GoBike_EDA.ipynb
│
├── images/
│
├── reports/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Collection & Integration
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business Insights
      │
      ▼
Recommendations
```

---

## 🧹 Data Preprocessing

The dataset was prepared through several preprocessing steps:

- Merged multiple monthly datasets
- Removed duplicate records
- Handled missing values
- Converted timestamp columns
- Filtered invalid age values
- Created new analytical features

### Engineered Features

- `ride_month`
- `ride_day`
- `ride_hour`
- `age`
- `ride_duration_min`

---

## 📈 Exploratory Data Analysis

### Univariate Analysis

- User Type Distribution
- Gender Distribution
- Age Distribution
- Monthly Ride Distribution
- Weekday Ride Distribution
- Hourly Ride Distribution
- Ride Duration Distribution
- Ride Duration Boxplot

### Bivariate Analysis

- Top Start Stations
- Top End Stations
- User Type vs Ride Duration
- Gender vs Ride Duration
- Age vs Ride Duration

### Multivariate Analysis

- Correlation Heatmap
- Pair Plot

---

## 💡 Key Insights

- Subscribers account for the majority of rides.
- Most riders belong to the **25–35 years** age group.
- Ride demand peaks during weekday commuting hours.
- October records the highest monthly ridership.
- Transit hubs are the busiest bike stations.
- Most trips last less than **15 minutes**.

---

## 📌 Business Recommendations

- Optimize fleet distribution at high-demand stations.
- Improve bike availability during peak commuting hours.
- Launch campaigns to convert casual customers into subscribers.
- Schedule maintenance during low-demand periods.
- Monitor unusually long rides to detect operational issues.

---

## 🚀 Future Scope

- Demand Forecasting using Machine Learning
- Customer Segmentation
- Interactive Power BI Dashboard
- Geospatial Analysis
- Weather-Based Demand Prediction
- Real-Time Bike Availability Analysis

---

## 📁 Dataset

Due to GitHub file size limitations, the datasets are hosted externally.

- **Raw Dataset:** Available in `data/raw`
- **Processed Dataset:** Available in `data/processed`

Each folder contains a download link to the corresponding Google Drive file.

---

## ▶️ Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/Ford-GoBike-EDA.git
```

### Navigate to the project

```bash
cd Ford-GoBike-EDA
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📄 Project Report

A comprehensive project report is available in the **reports/** directory, detailing the methodology, analysis, visualizations, business insights, and recommendations.

---

## 👨‍💻 Author

**Kaustubh Sahu**

Aspiring Data Analyst

**Skills:** Python • SQL • Excel • Power BI • Data Visualization • Exploratory Data Analysis

---

## ⭐ If you found this project useful, consider giving it a star!
