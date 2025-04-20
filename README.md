# 📊 SmartPoint – Enterprise Sales Performance Dashboard (Power BI Project)

## 🧠 Project Overview

The **SmartPoint Sales Performance Dashboard** is a comprehensive Power BI project built to evaluate and monitor the **overall business health** of SmartPoint — a national enterprise retail brand.

The primary goal of this analysis is to empower stakeholders with **actionable insights** through key performance indicators (KPIs) such as **monthly sales trends, profit margins, regional performance, and product category analysis**. By implementing an efficient **ETL pipeline** and leveraging the capabilities of Power BI's visual analytics, the dashboard presents a clear picture of how the business is performing across different dimensions.

This end-to-end data analytics project was executed using:
- **SQL** for initial data preparation and cleaning.
- **Power BI Desktop** for data modeling, transformation, and dashboard creation.

---

## 🗃️ Database Information

This project uses three key datasets in `.csv` format:

- **SmartPoint - SalesTable.csv**  
  Contains sales transaction records including product IDs, sales amount, profit, and region-wise details.

- **SmartPoint - ProductTable.csv**  
  Includes hierarchical product information like category, sub-category, and classification.

- **SmartPoint - DateTable.csv**  
  A date dimension table used for building time intelligence, enhanced with month names, numbers, and years.

📁 **Dataset Link**: [[Insert dataset link here](https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/SmartPoint%20-%20SalesTable.csv)]

---

## 🔄 ETL Process in Power BI

A structured **ETL (Extract, Transform, Load)** process was followed to build a scalable and meaningful data model.



## ❓ Business Questions Answered

The dashboard is designed to answer the following key business questions:

- How have **monthly sales and profit percentages** evolved over the year?
- Which **product categories and sub-categories** are contributing the most to revenue?
- Which **regions and cities** are the most profitable or underperforming?
- What is the **Pareto distribution** of sales — i.e., which 20% of products are bringing in 80% of the revenue?
- How does **product hierarchy** impact profitability?

---

## 📊 EDA & Visualizations

This Power BI solution includes **three interactive report tabs**:

### 1️⃣ Monthly Sales/Profit%
- Visuals:
  - Line chart showing **monthly sales trends**.
  - Card visual for **Profit %**.
  - **Pareto Chart**: Highlights top-performing products (80/20 rule).
  - Helps track **seasonal performance** and identify high-growth periods.
> 🖼️ Monthly Sales/Profit% Dashboard

![Monthly Sales/Profit% Dashboard](https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/_SmartPoint%20Monthly%20Sales_Profit.png)

### 2️⃣ Sales by Product Hierarchy
- Visuals:
  - **Decomposition Tree**: Analyzes revenue and profit at multiple levels of product hierarchy.

  - Enables focused product strategy and inventory planning.
> 🖼️ Sales by Product Hierarchy Dashboard

![Sales by Product Hierarchy Dashboard](https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/_SmartPoint%20Sales%20by%20Product%20Hierarchy.png)

### 3️⃣ Region
- Visuals:
  - **Map Visualization**: Displays total sales across different **cities and regions**.
  - Highlights high and low performing regions for strategic market development.

> 🖼️ Region Dashboard

![Region Dashboard](https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/_Smartpoint%20Region-wise%20Sales1.png)
![Region Dashboard](https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/_Smartpoint%20Region-wise%20Sales2.png)
![Region Dashboard](https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/_Smartpoint%20Region-wise%20Sales3.png)


---

## 🔍 Key Insights

- **Strong seasonal trends** observed, with sales peaking during specific months—indicating promotional campaign impact or seasonal demand.
- The **Pareto chart** reveals that a **small portion of products contribute to a majority of revenue**, validating the need for focused marketing.
- Certain regions show **high revenue but lower profitability**, indicating possible operational inefficiencies.
- The **Decomposition Tree** provided drill-down capabilities to identify high-earning subcategories.

---

## 🛠️ Tools & Technologies Used

- **Google Sheets** – for initial cleaning, validation, and preprocessing of raw CSV files.
- **Power BI Desktop** – for:
  - Data modeling and relationship building
  - DAX measures and calculated columns
  - Interactive dashboard creation (Map, Decomposition Tree, Pareto, Line Charts)

---

## 📎 Resources

- 📁 **Dataset Link**: [https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/SmartPoint%20-%20SalesTable.csv]  
- 📈 **Power BI Dashboard Link**: [https://github.com/rashi12121/SmartPoint-Enterprise_Sales_Performance/blob/main/_SmartPoint%20Monthly%20Sales_Profit.png]

---


