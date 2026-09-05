# E-Commerce Sales & Fulfillment Analysis 🛒📊

## Project Overview
This project demonstrates an end-to-end data analytics pipeline. It starts with raw, messy e-commerce sales data, performs data cleaning and exploratory data analysis (EDA) using Python, and culminates in an interactive Power BI dashboard. The core objective is to identify key revenue drivers, analyze discount effectiveness, and pinpoint regional logistical bottlenecks.

## 🛠️ Tech Stack
* **Data Cleaning & Wrangling:** Python (Pandas)
* **Exploratory Data Analysis:** Jupyter Notebook, Matplotlib, Seaborn
* **Interactive Dashboard:** Power BI

## 💡 Key Business Insights Discovered
1. **The Revenue Driver:** The South region leads in total volume, with *Running Shoes* and *Backpacks* driving the highest net revenue across all categories.
2. **The Logistics Risk:** Despite processing lower overall volume, the East region has a critical 25% fulfillment failure rate (cancelled/returned orders), indicating a need for immediate logistical review.
3. **The Margin Leak:** Heavily discounting low-ticket items (e.g., USB Chargers at 11.5% off) fails to drive significant sales volume and primarily dilutes net profit margins.

## 📊 Power BI Dashboard Preview
*The dashboard features cross-filtering capabilities, allowing users to slice revenue and fulfillment metrics dynamically by product category.*

<!-- Displaying the main dashboard screenshot -->
![Dashboard View](Screenshot%202026-09-05%20231145.png)

> **Note to Recruiters:** You can download the `E-Commerce Sales & Fulfillment Dashboard.pbix` file from this repository to interact with the full dashboard, or review the `ecommerce_analysis.ipynb` file to see the Python data cleaning process.
