# 🌾 Smart Farm Profit Analysis Dashboard

## Veda Technology – Data Analytics Internship

This project was developed as part of the **Veda Technology Data Analytics Internship – Task 16**.

The project focuses on analyzing revenue and profit from a Smart Farm Market dataset using Python and interactive visualization techniques.

---

## 🎯 Objective

The main objectives of this project are:

- Analyze total revenue and profit
- Calculate average profit
- Analyze crop-wise profitability
- Compare revenue and profit
- Calculate profit margins
- Analyze demand levels
- Analyze buyer types
- Identify high-revenue and low-profit records
- Build an interactive live dashboard

---

## 📊 Dataset

Dataset:

`Smart_Farm_Market_Analytics.csv`

The dataset contains information related to:

- Farm
- Crop
- District
- Season
- Yield
- Market Price
- Revenue
- Transport Cost
- Profit
- Demand Level
- Buyer Type
- AI Advisory

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- ipywidgets
- Google Colab
- OpenPyXL
- Microsoft Excel
- GitHub

---

## 📈 Analysis Performed

### 1. Profit Summary

Calculated:

- Total Revenue
- Total Profit
- Average Profit
- Profit Margin

### 2. Crop-wise Profit Analysis

Profit was grouped according to crop to understand profitability differences.

### 3. Revenue vs Profit

Revenue and profit were compared using interactive charts.

### 4. Profit Margin

Profit margin was calculated using:

Profit Margin = Profit / Revenue × 100

### 5. Demand Analysis

Profit was analyzed according to demand level.

### 6. Buyer Analysis

Profit was analyzed based on buyer type.

### 7. Revenue vs Profit Relationship

A scatter plot was created to identify the relationship between revenue and profit.

---

## 📊 Dashboard Features

The interactive dashboard contains:

- Crop filter
- District filter
- Season filter
- Total Revenue KPI
- Total Profit KPI
- Average Profit KPI
- Total Yield KPI
- Average Market Price KPI
- Transport Cost KPI
- Profit Margin KPI

### Charts

- Profit by Crop
- Revenue vs Profit
- Revenue vs Profit Scatter Plot
- Profit Margin by Crop
- Profit by Demand Level
- Profit by Buyer Type

---

## 💡 Key Business Question

### Why can sales/revenue be high but profit low?

High revenue does not always mean high profit.

Profit can be affected by:

- Transportation costs
- Production costs
- Market price
- Low-margin crops
- Other operational expenses

Therefore, revenue and profit should be analyzed separately.

---

## 📂 Project Structure

```text
smart-farm-profit-analysis/
│
├── Smart_Farm_Market_Analytics.csv
├── Task_16_Profit_Analysis.ipynb
├── Task_16_Smart_Farm_Final_Report.xlsx
├── Task_16_Graphs/
│   ├── 01_Profit_by_Crop.png
│   ├── 02_Revenue_vs_Profit.png
│   ├── 03_Revenue_vs_Profit_Scatter.png
│   └── 04_Profit_Margin.png
│
└── README.md
