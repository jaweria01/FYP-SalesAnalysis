# SuperStore Sales Analysis (FYP)

## 📌 Overview
This project is a Final Year Project (FYP) that focuses on analyzing retail store sales data to extract business insights. Data preprocessing and EDA are performed to identify patterns and trends. Machine learning models are applied for sales forecasting, customer segmentation, and product analysis. Visualizations highlight top-performing categ, regional sales, and loss-making items.

-**Problem:**

The retail industry is highly competitive and dynamic, with businesses facing numerous challenges such as changing consumer behavior, increasing competition, regional sales variations. Moreover,difficulty in tracking overall performance across multiple dimensions (category, region, customer, and time). and shifting market trends.

In such an environment, it is crucial for businesses to have a deep understanding of their sales performance to remain competitive and drive growth.
Without effective analysis, companies struggle to identify profitable areas, manage losses, and make timely, data-driven decisions.

**- Solution :** 

The Superstore dataset provides an opportunity to conduct an in-depth analysis of sales performance, enabling businesses to gain valuable insights into their sales performance, identify areas of strength and weakness, and make data-driven decisions to improve their sales processes. To conduct the sales analysis on the Superstore dataset, Python, Streamlit, Pandas, and Plotly. are used to create interactive dashboards and reports.

- It analyzes Superstore sales data through interactive dashboards.
- It enables users to explore, clean, and visualize sales records, while applying techniques like outlier detection, filtering, time series analysis, and trend visualization.
Built with Streamlit + Plotly, the dashboard is designed for data-driven decision making in retail sales.

- The sales analysis on Superstore dataset is a study aimed at analyzing the sales performance of a fictional retail company called **"Superstore"**. The analysis utilizes a dataset containing information about sales transactions, customers, products, and geographical locations. 



🔗 **Live Demo**: [Superstore Sales Dashboard](https://fyp-salesanalysis-01.streamlit.app/)

<img width="1359" height="608" alt="Project_Sales" src="https://github.com/user-attachments/assets/acd8a6e5-eb38-43ba-b840-99454a21f25a" />

<img width="1057" height="543" alt="Project_Graph" src="https://github.com/user-attachments/assets/a1991fb4-963c-424a-9e99-3f630e579c5b" />


---
### 🎯 Features

✅ File uploader for CSV, TXT, XLS, XLSX datasets (up to 200MB)

✅ Interactive filtering by Country, Region, State, and City

✅ **Data Exploration:**

- Show dataset head, tail, info, shape, columns, and summary
- Detect missing values, duplicates, and outliers (Z-score & IQR)
- Fill missing values and download the cleaned dataset
- 
✅ **Data Visualizations:**

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

**1. Clone the repository**
```
git clone https://github.com/<your-username>/FYP-SalesAnalysis.git
cd FYP-SalesAnalysis
```

**2. Install dependencies**
```
pip install -r requirements.txt
```
**3. Run the app**
```
streamlit run superstore_app.py
```
**4. Open the provided URL (default: http://localhost:8501) in your browser.**

## 🚀 Deployment on Streamlit Cloud

- Push this repo to GitHub.
- Go to Streamlit Community Cloud
- Create a New App → Select your repo + branch → set Main file path to:
- superstore_app.py
- Deploy 🎉 → Share your app using the public link.

## 📊 Sample Insights

- Technology contributes the highest revenue.
- Punjab leads state-wise sales in the dataset.
- Standard Class dominates shipping mode (~60%).
- Clear seasonal variations visible in time-series sales trends.
- Profit margins vary significantly by category & discounting policies.

## 🚀 Future Enhancements

**🔮Machine Learning Forecasting**

- Apply ARIMA/Prophet/LSTM models for future sales & profit predictions.

👥 **Customer Segmentation**

- Use clustering (K-Means, DBSCAN) to identify customer groups and improve targeted marketing.

🛒 **Market Basket Analysis**

- Recommend frequently bought products together (using Apriori / FP-Growth).

📡 **Real-Time Data Integration**

- Connect with SQL / live APIs to analyze data dynamically rather than static CSVs.

📊 **Advanced BI Dashboard**

- Deploy dashboards in Tableau or Power BI alongside Streamlit for more visual insights.

**☁️ Cloud Deployment**

- Host on AWS / Azure / GCP for scalability and enterprise-level use.

## 📜 License

This project is licensed under the MIT License – free to use with attribution.
✨ A complete FYP combining Data Cleaning, Visualization, and Interactive Dashboards to empower retail business intelligence.


[Superstore!!! · Streamlit.pdf](https://github.com/user-attachments/files/22053268/Superstore.Streamlit.pdf)






