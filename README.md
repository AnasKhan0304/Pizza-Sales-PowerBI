# 🍕 Pizza Sales Analysis — Power BI

An interactive Power BI dashboard built to analyze pizza sales performance, order patterns, product performance, and revenue trends.

## 📊 Project Overview

This project analyzes pizza sales data to identify the products, categories, sizes, time periods, and ordering patterns that contribute most to sales.

The dashboard is designed as an interactive business intelligence report using Power BI, with a dimensional data model and multiple KPI and analytical visuals.

## 🎯 Objectives

- Analyze overall pizza sales and order performance
- Identify the best-performing pizzas and categories
- Understand sales patterns by month, weekday, and hour
- Compare pizza sizes and categories by quantity sold
- Examine ingredient-level demand
- Provide interactive filtering for deeper analysis

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard development and visualization
- **DAX** — Measures and analytical calculations
- **Power Query** — Data preparation and transformation
- **Data Modeling** — Fact and dimension modeling

## 🧩 Data Model

The report uses a dimensional model built around the main `Pizza Sales` table and supporting dimension tables:

- `Pizza Sales` — sales and order-level transactional data
- `DimDate` — date and time analysis
- `DimPizza` — pizza attributes
- `DimPizzaName` — pizza naming/details
- `Ingredients` — ingredient-level analysis

## 📈 Dashboard Analysis

### Sales & Order Performance

The dashboard provides key performance indicators including:

- Total Sales
- Total Orders
- Total Pizzas Sold
- Average Order Value
- Average Pizzas per Order

### Time Analysis

Sales and order activity can be analyzed across:

- Month
- Weekday
- Hour of day

This helps identify peak ordering periods and recurring sales patterns.

### Product Analysis

The report examines:

- Top 5 pizzas by sales
- Sales by pizza category
- Quantity sold by pizza size
- Category and size performance
- Ingredient demand

### Interactive Analysis

Users can filter the dashboard by pizza category and explore the underlying sales patterns through interactive Power BI visuals.

## 💡 Key Business Questions

This dashboard can be used to answer questions such as:

1. Which pizzas generate the most revenue?
2. Which pizza categories perform best?
3. What are the busiest ordering hours?
4. Which weekdays generate the highest sales?
5. Which pizza sizes are ordered most frequently?
6. Which ingredients have the highest demand?


## 📌 Project Type

**Data Analytics | Business Intelligence | Power BI**

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.

> Dataset and third-party assets, where applicable, remain subject to their original licenses and ownership.
