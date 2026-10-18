# Supply-Chain-Analysis
## 📌 Project Overview

This project is an exploratory data analysis (EDA) of the **DataCo Smart Supply Chain dataset**, which contains order, shipping, customer and product data for a global supply chain company.
The goal is to understand how efficiently orders are processed and delivered, and how delivery performance relates to profitability. The analysis covers:
- **Data cleaning:** removing sensitive and irrelevant columns (e.g. customer email, password, IDs), dropping cancelled orders and fixing date formats
- **Feature engineering:** order processing time, shipping delay, delayed-order flag, order month, day and hour, and a profit / loss / break-even flag
- **Exploratory analysis:** patterns in delays and profitability across time, products and shipping modes

**Tools used:** 
Python, 
Pandas, 
NumPy, 
Matplotlib, 
Seaborn.

**Dataset:** [DataCo Smart Supply Chain for Big Data Analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) (Kaggle). Download `DataCoSupplyChainDataset.csv` and place it in the project folder before running the notebook.

## ❓ Problem Statement

Late deliveries hurt customer satisfaction and increase costs for any supply chain business. At the same time, not every order is profitable, and some orders end up making a loss.

This project aims to answer the following questions:

1. How many orders are delivered late, and how large is the gap between scheduled and actual shipping time?
2. Which factors (shipping mode, order timing, product category, region) are linked to delays?
3. How many orders are profitable, loss-making or break-even?
4. Is there a relationship between delivery delays and order profitability?

The findings can help the business reduce delays, improve planning and focus on the most profitable orders.
