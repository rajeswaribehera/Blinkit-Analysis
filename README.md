# 📊 Blinkit Sales Analysis Dashboard

An interactive Power BI dashboard project built to analyze and visualize Blinkit's sales data. The dashboard delivers insights into total sales, item categories, outlet performance, and customer ratings to support strategic, data-driven decisions in the retail domain.

---

## 🧠 Project Objective

The objective of this project is to build a comprehensive Power BI dashboard that:

- Analyzes sales performance across multiple outlets and product categories.
- Visualizes KPIs such as Total Sales, Average Sales, Number of Items Sold, and Customer Ratings.
- Supports decision-making for outlet management, product strategy, and customer engagement.

---

## 📂 Dataset Overview

The dataset includes the following key features:

- **Item Identifier**: Unique product ID  
- **Item Type**: Categories like Dairy, Fruits, Snacks, etc.  
- **Item Fat Content**: Regular, Low Fat, etc.  
- **Outlet Identifier**: Unique store ID  
- **Outlet Type**: Grocery Store, Supermarket Types 1-3  
- **Outlet Location Type**: Tier 1, Tier 2, Tier 3  
- **Outlet Size**: Small, Medium, High  
- **Outlet Establishment Year**  
- **Item Weight**  
- **Item Visibility**  
- **Sales**  
- **Customer Rating** (Scale: 1–5)

---

## 🛠️ Tools & Technologies Used

- **Power BI** – For dashboard creation and visualization  
- **DAX (Data Analysis Expressions)** – For calculated measures and KPIs  
- **Power Query** – For data cleaning and transformation

---

## 📈 Key Features of the Dashboard

- **KPI Cards**: Total Sales, Avg. Sales, Items Sold, Avg. Rating  
- **Bar & Donut Charts**: Item category and outlet type performance  
- **Line Chart**: Yearly sales trends  
- **Tables**: Outlet type comparisons  
- **Filters/Slicers**: Outlet size, item type, and location filters  
- **Interactivity**: Cross-filtering and tooltips for deeper analysis

---

## 📊 Key Metrics Calculated (DAX)

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
Number of Items = COUNTROWS('BlinkIT Grocery Data')
