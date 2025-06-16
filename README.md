# Retail Revenue Insights: Tata Group Case Study

## 📌 Project Overview  
This project was part of a job simulation for Tata Group, focused on analyzing retail store performance using a dataset of transactions. The goal was to support business decisions by cleaning raw data, identifying key revenue trends, and presenting insights through clear visualizations.

I was tasked with uncovering trends in revenue across countries, identifying top-performing customers and products, and analyzing product demand by region. The final output was a Power BI dashboard tailored for executive decision-makers.

---

## Dataset Overview  
The dataset represented retail transaction data from 2010–2011 and included the following columns:

- `Invoice No`
- `Stock Code`
- `Description`
- `Quantity`
- `Invoice Date`
- `Unit Price`
- `Customer ID`
- `Country`

The dataset had missing values, irregularities, and required cleaning before use.

---

## Data Cleaning & Preparation

Steps taken in Power BI (Power Query):

- Removed rows with missing `Customer ID`
- Filtered out transactions with non-positive Quantity or Price
- Converted `Invoice Date` to proper datetime format
- Extracted `Month` and `Year` for time-based analysis
- Standardized column headers for clarity

---

## Business Questions & Visualizations

### 1. Monthly Revenue Trends in 2011 (Time Series)
- **Goal:** Show seasonal revenue trends for 2011
- **Visual:** Line chart (Revenue by Month)
- **Insight:** Q4 (especially November & December) had peak revenue
- ![Revenue Data for 2011](https://github.com/user-attachments/assets/85c05add-d2d6-4d60-a193-8dfa055c26c4)


### 2. Top 10 Countries by Revenue (excluding UK)
- **Goal:** Help the CMO identify non-UK markets with high revenue and quantity sold
- **Visual:** Bar chart (Country vs Revenue + Quantity)
- **Insight:** Netherlands, Germany, and France showed high demand and strong revenue
- ![Countries by Revenue   Quantity](https://github.com/user-attachments/assets/3f0e97be-2215-46ad-817d-dda0c8cb3b10)
  

### 3. Top 10 Customers by Revenue
- **Goal:** Identify highest revenue-generating customers for retention strategies
- **Visual:** Descending bar chart (CustomerID vs Revenue)
- **Insight:** Small group of customers generated a large share of revenue
- ![Top Customers by Revenue](https://github.com/user-attachments/assets/ca6f9f90-de69-4020-93b6-9eb1ebd28166)


### 4. Country-Level Product Demand (excluding UK)
- **Goal:** Show regions with the greatest product demand for expansion
- **Visual:** Basic Map and Table (Country vs Quantity Sold)
- **Insight:** Germany, Netherlands, and France showed highest demand
- ![Product Demand by Country](https://github.com/user-attachments/assets/cdce6033-0e9f-4a9b-9af4-f36b28af7c11)

---

## 💡 Insights & Recommendations

- **Capitalize on Q4 spikes:** Plan inventory and marketing ahead of peak months.
- **Target high-potential regions:** Focus expansion in top-demand countries outside the UK.
- **Retain top customers:** Develop personalized strategies to retain key customers.
- **Match demand with supply:** Align operations with countries showing consistently high product volumes.

---

## 🛠️ Tools Used  
- **Power BI** (visualization & DAX)
- **Power Query** (data cleaning)
- **Excel** (initial exploration)

---

Connect with me on [LinkedIn](https://www.linkedin.com/in/philipdagadu/)
