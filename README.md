# FYP-SalesAnalysis
This project focuses on analyzing retail store sales data to extract business insights. Data preprocessing and EDA are performed to identify patterns and trends. Machine learning models are applied for sales forecasting, customer segmentation, and product analysis. Visualizations highlight top-performing categ, regional sales, and loss-making items

## 🛒 Superstore Sales Analysis – Interactive Dashboard

📌 Overview

This project is a Final Year Project (FYP) that analyzes Superstore sales data through interactive dashboards.
It enables users to explore, clean, and visualize sales records, while applying techniques like outlier detection, filtering, time series analysis, and trend visualization.
Built with Streamlit + Plotly, the dashboard is designed for data-driven decision making in retail sales.

🔗 **Live Demo**: [Superstore Sales Dashboard](https://fyp-salesanalysis-01.streamlit.app/)

---
### 🎯 Features

✅ File uploader for CSV, TXT, XLS, XLSX datasets (up to 200MB)
✅ Interactive filtering by Country, Region, State, and City
✅ Data Exploration:

- Show dataset head, tail, info, shape, columns, and summary

- Detect missing values, duplicates, and outliers (Z-score & IQR)

- Fill missing values and download the cleaned dataset
✅ Data Visualizations:

**Bar Charts:** Category, Sub-Category, Yearly, Region, State, Segment-wise sales

**Pie Charts:** Segment, Category, Region, Ship Mode, State sales %

**Line Chart:** Time Series sales trends

**Treemap:** Hierarchical view of Region → Category → Sub-Category

**Scatter Plot:** Relationship between Sales & Profit
✅ Downloadable summary tables for further offline analysis

---
## 🛠 Tech Stack

- Frontend / Dashboard: Streamlit

- Visualization: Plotly Express, Matplotlib

- Data Handling: Pandas, NumPy

- Statistical Analysis: SciPy

- Other: Python 3.9+, Jupyter Notebook (for development)

---

📂 Project Structure
```
FYP-SalesAnalysis/
│── superstore_app.py       # Main Streamlit app
│── sales_data.csv          # Sample dataset
│── requirements.txt        # Dependencies
│── README.md               # Documentation
```

## ⚙️ How to Run Locally

1. Clone the repository
```
git clone https://github.com/<your-username>/FYP-SalesAnalysis.git
cd FYP-SalesAnalysis
```

2. Install dependencies
```
pip install -r requirements.txt
```
3. Run the app
```
streamlit run superstore_app.py
```
4.Open the provided URL (default: http://localhost:8501) in your browser.

## 🚀 Deployment on Streamlit Cloud

- Push this repo to GitHub.

- Go to Streamlit Community Cloud

- Create a New App → Select your repo + branch → set Main file path to:

- superstore_app.py

- Deploy 🎉 → Share your app using the public link.

## 📊 Sample Insights

Technology contributes the highest revenue.

Punjab leads state-wise sales in the dataset.

Standard Class dominates shipping mode (~60%).

Clear seasonal variations visible in time-series sales trends.

Profit margins vary significantly by category & discounting policies.

## 📜 License

This project is licensed under the MIT License – free to use with attribution.

✨ A complete FYP combining Data Cleaning, Visualization, and Interactive Dashboards to empower retail business intelligence.


