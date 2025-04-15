# Solar-Generation-Vs-Electricity-Usage-Analysis
# ☀️ Solar Generation vs Electricity Usage Analysis 🔌

This project explores and analyzes the relationship between **solar electricity generation** and **electricity consumption** using a real-world dataset. The analysis includes data cleaning, exploratory data analysis (EDA), outlier detection and removal, time-based trend analysis, and energy balance modeling, such as electricity bought and excess solar generated.

## 📊 Project Objective

To understand energy generation patterns from solar sources versus actual electricity usage in order to:
- Detect seasonal trends.
- Identify periods of energy surplus or deficit.
- Model electricity dependency and potential storage optimization.

---

## 📁 Contents

- **Data Cleaning & Exploration**
- **Univariate, Bivariate & Multivariate Analysis**
- **Outlier Detection & Removal using IQR**
- **Time-Series Feature Extraction**
- **Monthly Electricity Trends**
- **Energy Balance Calculations**
- **Battery Charge Simulation**

---

## 🔧 Tools Used

- Python 🐍
- Pandas 📊
- NumPy 🔢
- Matplotlib 📈
- Seaborn 🌊
- PostgreSQL (via SQLAlchemy)

---

## 📦 Data Pipeline

1. **Data Source**: PostgreSQL database connection using SQLAlchemy.
2. **Data Cleaning**:
   - Dropped nulls and unnecessary columns.
   - Converted date strings to `datetime` objects.
   - Handled outliers using the Interquartile Range (IQR) method.
3. **Feature Engineering**:
   - Extracted month names for seasonality insights.
   - Calculated electricity bought and excess solar energy.
   - Modeled a simple battery storage system (max 12.5 kWh).
4. **Visualization**:
   - Monthly generation vs consumption comparisons.
   - Boxplots for outliers.
   - Bar charts and pie charts for seasonal trends.
   - Line plots for average hourly usage and generation.

---

## 📈 Key Insights

- **Monthly Trends**: Electricity usage and solar generation vary significantly by month.
- **Outlier Impact**: Removing outliers enhanced clarity in monthly patterns.
- **Energy Surplus**: Certain months had notable excess solar generation.
- **Battery Simulation**: A basic model tracks how much excess solar could be stored and used.

---
