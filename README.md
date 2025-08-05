# 🍋 Lemon Price Analysis Across Indian Mandis (2022–2024)

This repository contains a comprehensive data science case study on analyzing lemon price and arrival trends across fruit and vegetable Mandis in India, using daily data from 2022 to 2024.

## 📌 Objective

The objective of this case study is to:
- Evaluate the dataset for missing data, outliers, and anomalies.
- Identify seasonal trends across states.
- Calculate average and seasonally adjusted lemon prices.
- Forecast lemon prices for the next two quarters.

## 📊 Dataset Overview

- Rows: 157,000+
- Columns: Date, Market, State, Arrivals (Tonnes), Modal Price (Rs./Quintal), Variety, Year, Month
- Source: Provided as part of the Data Scientist evaluation by IndiaDataHub


## 📈 Analysis & Methodology

### ✅ 1. Data Cleaning & Quality Checks
- Missing value analysis
- Duplicate detection
- Anomaly detection using Z-scores

### 🌦️ 2. Seasonality Analysis
- Monthly average price trends
- Seasonal decomposition using `statsmodels`

### 📉 3. Outlier Removal
- Applied statistical thresholds to remove noise
- Ensured clean data before forecasting

### 🧠 4. Forecasting
- Applied Facebook Prophet to forecast prices for the next 6 months
- Captured yearly seasonality and long-term trends


## 💡 Key Insights

- Lemon prices peak in summer (Apr-May) and dip during monsoons and winter.
- Seasonal demand (e.g., festivals) significantly influences price.
- Despite high arrivals in some months, prices remain high — demand outpaces supply.

---

## 👩‍💻 Author

**Shruti Satam**  
[LinkedIn](https://www.linkedin.com/in/shruti-satam-)  


## 📬 Contact

For any queries or collaborations, feel free to reach out:  
📧 shrutisatam@gmail.com  
