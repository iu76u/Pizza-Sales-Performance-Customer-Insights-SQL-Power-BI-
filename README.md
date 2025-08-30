# 🍕 Pizza Sales Performance & Customer Insights (SQL & Power BI)
-End-to-end analysis of pizza sales using SQL and Power BI to highlight business opportunities.Showcasing strong data cleaning, visualization, and communication skills for real-world impact

## 📌 Table of Contents  
- [Overview](#-overview)  
- [Business Problem](#-business-problem)  
- [Dataset](#-dataset)  
- [Tools & Technologies](#-tools--technologies)  
- [Project Structure](#-project-structure)  
- [Data Cleaning & Preparation](#-data-cleaning--preparation)  
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  
- [Research Questions & Key Findings](#-research-questions--key-findings)  
- [Dashboard](#-dashboard)  
- [How to Run This Project](#-how-to-run-this-project)  
- [Final Recommendations](#-final-recommendations)  
- [Author & Contact](#-author--contact)  

---

## 📌 Overview  
This project analyzes **pizza sales data** using **SQL** for querying and **Power BI** for visualization.  
The goal is to uncover sales trends, customer behavior, and performance insights to support data-driven decision-making.  

---

## 💡 Business Problem  
A pizza store collects daily sales data but struggles to interpret it effectively.  
The objective is to transform raw data into **actionable insights**—identifying top products, sales patterns, and improvement opportunities.  

---

## 📊 Dataset  
- Source: Pizza sales transaction data (orders, pizzas, quantities, prices, etc.)  
- Size: ~48k rows (depending on dataset version)  
- Columns include: `OrderID`, `Date`, `PizzaName`, `Category`, `Size`, `Quantity`, `Price`, etc.  

---

## 🛠 Tools & Technologies  
- **SQL** → Data cleaning, transformation, and KPI calculations  
- **Power BI** → Dashboard design and visualization  
- **Excel/CSV** → Raw data storage  

---

## 📂 Project Structure  
📁 Pizza-Sales-Performance-Customer-Insights-SQL-Power-BI  
│  
├── PIZZA SALES.sql               # SQL queries for cleaning and KPI generation  
├── pizza sales analysis.pbix     # Power BI dashboard file  
├── images/                       # Exported PNG screenshots of dashboards  
└── README.md                     # Project documentation  

---

## 🧹 Data Cleaning & Preparation  
- Removed duplicates and missing values  
- Standardized pizza categories and sizes  
- Created calculated fields: **Total Bill**, **Day of Week**, **Hour of Sale**  
- Ensured consistency for time-based analysis  

---

## 🔎 Exploratory Data Analysis (EDA)  
- **Time Trends** → Hourly & daily sales distribution  
- **Branch Analysis** → Revenue contribution by category/size  
- **Product Demand** → Best & worst-selling pizzas  
- **Customer Behavior** → Average order size, repeat preferences  

---

## ❓ Research Questions & Key Findings  
1. **When do customers order the most pizzas?**  
   → Peak hours: **Friday & Saturday evenings (6–8 PM)**  
2. **Which pizzas generate the highest revenue?**  
   → *Classic Deluxe Pizza* and *Large Sizes*  
3. **Which pizzas perform poorly?**  
   → Certain specialty pizzas contribute <2% of sales  
4. **What is the average order value?**  
   → ~$38 per order  

---

## 📊 Dashboard 
  

### ⭐ KPI Overview  
![KPI Dashboard](images/kpi_dashboard.png)  

### 📅 Sales Trends  
![Sales Trend](images/sales_trend.png)  

### 🍕 Pizza Performance  
![Pizza Performance](images/pizza_performance.png)  

### 📂 Category Insights  
![Category Insights](images/category_insights.png)  

---

## 🚀 How to Run This Project  
1. Clone/download this repository  
2. Run `PIZZA SALES.sql` in your SQL environment to generate KPIs & insights  
3. Open `pizza sales analysis.pbix` in **Power BI Desktop**  
4. Explore interactive dashboards for trends and patterns  

---

## 📝 Final Recommendations  
- 📈 **Staffing** → Increase staff during evening peak hours  
- 🍴 **Menu Optimization** → Promote *Classic Deluxe* and high-margin items  
- 🎁 **Marketing Strategy** → Offer bundled deals for large-sized pizzas  
- 📊 **Future Work** → Add customer demographics for deeper personalization  

---

## 👤 Author & Contact  
**T V Shreyas Kumar**  
- 💼 LinkedIn: www.linkedin.com/in/shreyas-kumar-7868ab228
- ✉️ Email: Shreyas291103@gmail.com
