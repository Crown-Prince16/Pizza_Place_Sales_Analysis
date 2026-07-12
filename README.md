# 🍕 Pizza Place Sales Analysis

An exploratory data analysis of a full year of sales from a fictitious pizza restaurant, built in Python with `pandas` and `matplotlib`. The project joins four raw CSV tables into a single analytical dataset and digs into revenue, order volume, timing patterns, and menu performance to answer a set of core business questions — and a few extra ones along the way.

## 📊 Overview

The dataset covers 12 months (2015) of order-level transactions from a pizza place, including the date and time of each order, the pizzas served, and details on type, size, quantity, price, and ingredients.

**Source tables:**

| Table | Description |
|---|---|
| `orders.csv` | One row per order, with date and time placed |
| `order_details.csv` | One row per pizza line item within an order (type, size, quantity) |
| `pizzas.csv` | Price and size for each pizza SKU |
| `pizza_types.csv` | Name, category, and ingredients for each pizza recipe |

All four tables are joined into a single dataframe — one row per pizza line item — before any analysis begins.

## ❓ Questions Answered

- What is the total revenue and total quantity sold?
- How many orders were placed, and how many pizza types are on the menu?
- What's the average price of a pizza?
- What are the peak hours of sales?
- Which day of the week generates the most revenue?
- What are the top 5 bestselling pizzas — by quantity *and* by revenue?
- Are there any monthly sales trends?
- Which pizza types are underperforming?

**Extended exploration:** revenue by pizza category, revenue by size, and the single busiest and slowest days of the year.

## 🔑 Key Insights

- **$817,860** in total revenue from **49,574 pizzas** across **21,350 orders** (avg. $38.31 per order)
- The menu has **32 pizza recipes** across 4 categories, offered in up to 5 sizes (96 total SKUs)
- Sales follow a **two-peak daily pattern**: a lunch rush (12–1pm) and a dinner rush (5–7pm)
- **Friday** is the strongest day of the week; **Sunday** is the weakest
- Revenue is **flat year-round** — no strong seasonal trend, with July the highest month and October the lowest
- **The Classic Deluxe Pizza** sells the most units, but **The Thai Chicken Pizza** and **The Barbecue Chicken Pizza** generate the most revenue thanks to higher price points
- **The Brie Carre Pizza** is the clear underperformer on the menu — lowest on both units sold and revenue
- **Large** is the dominant size, driving 46% of all revenue
- The day after Thanksgiving was the single busiest sales day of the year, ~3.5x an average day

## 🛠️ Tools & Libraries

- Python 3
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📄 License

This project uses a publicly available sample dataset for educational and portfolio purposes.
