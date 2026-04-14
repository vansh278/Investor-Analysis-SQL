# Solving-Inventory-Inefficiencies-Using-SQL

This project offers a complete SQL-powered analytical toolkit for evaluating, forecasting, and optimizing inventory management across multiple stores and warehouse locations. It leverages historical sales data, real-time stock levels, seasonality, weather, and product categories to compute actionable KPIs and guide supply chain decisions.

---

## 📌 Objective

To enable inventory-driven organizations to:
- Monitor and summarize current stock levels
- Predict when products should be reordered
- Flag stockouts and overstocked items dynamically
- Classify products based on their sales velocity
- Benchmark inventory health across locations
- Align actual sales with forecasted demand

---

## 🗂️ Database Schema Overview

The system expects a normalized schema with the following tables:

| Table              | Description                                      |
|-------------------|--------------------------------------------------|
| `stores`          | Maps store IDs to inventory and product IDs      |
| `inventory`       | Tracks daily units sold, stock levels, demand    |
| `external_factor` | Links store-inventory to season and weather      |
| `seasonality`     | Provides seasonal context (`season_id`)          |
| `weather`         | Describes weather conditions per `weather_id`    |
| `category`        | Contains product category labels                 |

---

