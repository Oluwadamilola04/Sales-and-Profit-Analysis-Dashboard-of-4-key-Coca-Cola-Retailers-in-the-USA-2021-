# Coca-Cola Sales Performance Dashboard (USA – 2021)

## 📌 Project Overview
This project is an **interactive Microsoft Power BI dashboard** that analyzes **Coca-Cola product sales across the United States in 2021**.  
The objective was to transform raw sales data into **clear, actionable insights** that help stakeholders understand revenue performance, profitability, regional demand, and product trends.

The dashboard provides a **high-level executive summary** as well as **detailed breakdowns** by time, brand, region, state, and retailer.

<img width="916" height="534" alt="Screenshot 2026-02-08 221531" src="https://github.com/user-attachments/assets/b733d0b4-4058-4c31-9ac6-4341e52ce211" />



---

## 🗂️ Dataset Scope
- **Company:** Coca-Cola  
- **Geography:** United States of America  
- **Time Period:** 2021  
- **Data Includes:**
  - Sales revenue
  - Units sold
  - Operating profit
  - Beverage brands
  - Retailers
  - States and regions

---

## 🧹 Data Cleaning & Preparation (Power Query)
The raw dataset was cleaned and transformed using **Power Query**:

- Removed duplicate and irrelevant records
- Standardized column names and formats
- Converted date fields into proper Date data types
- Handled missing and null values
- Created calculated columns for:
  - Total Sales
  - Operating Profit
- Extracted time attributes:
  - Month
  - Year
- Ensured consistent naming for:
  - Beverage brands
  - States
  - Regions
  - Retailers

---

## 🧱 Data Modeling
- Built a star-style data model with fact and dimension tables
- Created relationships between:
  - Sales
  - Products
  - Retailers
  - Geography
  - Time
- Developed DAX measures for:
  - Total Sales
  - Total Units Sold
  - Total Operating Profit
  - Monthly trends
  - Regional performance
- Optimized the model for interactivity and performance

---

## 📊 Dashboard Insights & Visual Analysis

<img width="912" height="516" alt="Screenshot 2026-02-08 221552" src="https://github.com/user-attachments/assets/addce6de-deec-4fd0-af7c-4eb72be7b612" />



### 🔢 KPI Summary Cards
- **Overall Total Sales:** `$8.68M`
- **Sum of Units Sold:** `17M`
- **Total Operating Profit:** `$3.17M`
- **Count of Retailers:** `4`

**Insight:**  
These KPIs provide an instant overview of Coca-Cola’s 2021 performance, showing strong revenue generation and profitability across a limited number of major retailers.

---

### 📈 Sales & Operating Profit by Month
- Displays monthly trends for:
  - Total Sales
  - Operating Profit
- Sales peak during **mid-year and end-of-year months**

**Insight:**  
Sales show clear seasonality, with higher performance during warmer months and year-end demand spikes.

---

### 🥤 Total Sales by Beverage Brand
- Coca-Cola leads total sales
- Followed by Dasani Water, Diet Coke, Sprite, Powerade, and Fanta

**Insight:**  
Core Coca-Cola products dominate revenue, while flavored and specialty drinks contribute smaller but consistent portions.

---

### 📦 Units Sold per Month
- Units sold increase significantly from mid-year onwards
- December records one of the highest unit volumes

**Insight:**  
Higher unit sales align with holiday seasons and promotional periods.

---

### 🌍 Units Sold per Region
- Strong performance in:
  - West
  - Southeast
  - Northeast

**Insight:**  
Regional demand varies, suggesting the need for region-specific marketing and distribution strategies.

---

### 💰 Operating Profit by Region
- The **West and Southeast** regions generate the highest operating profit

**Insight:**  
High sales volume does not always equate to high profit—profitability depends on regional cost efficiency.

---

### 🏬 Total Sales by Retailer
- Sodapop is the top revenue-generating retailer
- Followed by FizzySip, BevCo, and DreamCo

**Insight:**  
A small number of retailers account for most sales, indicating high retailer concentration.

---

### 🏬 Operating Profit by Retailer
- Sodapop leads in operating profit
- Profit margins vary significantly across retailers

**Insight:**  
Some retailers generate strong sales but lower profit, highlighting margin optimization opportunities.

---

### 🗺️ Total Sales by State
- Top-performing states include:
  - California
  - New York
  - Texas
  - Florida

**Insight:**  
Large population states contribute the most to overall revenue, aligning with market size expectations.

---

### 🗺️ Operating Profit by State
- States such as Florida, New York, and California show strong profitability

**Insight:**  
Certain states combine high demand with efficient operations, making them strategic markets.

---

### 🔍 Interactive Filters
- City
- State
- Beverage Brand
- Retailer

**Insight:**  
Filters allow users to drill down into specific markets, products, or retailers for deeper analysis.

---

## ✅ Key Business Insights
- Coca-Cola remains the dominant brand by both revenue and units sold
- Sales exhibit strong seasonal patterns
- A small group of retailers drive the majority of sales and profit
- Regional performance varies significantly between sales volume and profitability
- High-population states are critical revenue drivers

---

## 🛠️ Tools & Technologies Used
- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Interactive Visual Analytics

---

## 🚀 Conclusion
This Power BI project demonstrates an **end-to-end business intelligence workflow**, from raw data cleaning to advanced interactive analytics.  
The dashboard delivers **clear, decision-ready insights** into Coca-Cola’s 2021 U.S. sales performance and can be used by executives, analysts, and sales managers to support data-driven decisions.

---

## 📌 Future Enhancements
- Add year-over-year comparison
- Include forecasting using time-series analysis
- Incorporate marketing and promotional data
- Drill-down by customer demographics


