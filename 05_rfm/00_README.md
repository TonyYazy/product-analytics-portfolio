# Auto Sales RFM Analysis

## Project Overview

This project focuses on customer segmentation using **RFM analysis** based on auto sales transaction data.

The goal of the project is to analyze customer purchasing behavior and divide customers into meaningful business segments, such as:

- Champions
- Loyal Customers
- New Customers
- At Risk VIP
- Lost Customers
- Regular Customers

The project includes basic data cleaning, exploratory data analysis, and RFM-based customer segmentation.

---

## Dataset

The dataset used in this project was downloaded from Kaggle:

**Auto Sales Data**  
Source: https://www.kaggle.com/datasets/ddosad/auto-sales-data

The dataset contains auto sales transaction records, including order details, customer information, product categories, sales amount, order status, and geographic information.

Main columns used in the analysis:

| Column | Description |
|---|---|
| `CUSTOMERNAME` | Customer or company name |
| `ORDERNUMBER` | Unique order identifier |
| `ORDERDATE` | Date of the order |
| `SALES` | Sales amount |
| `QUANTITYORDERED` | Number of items ordered |
| `PRICEEACH` | Price per item |
| `STATUS` | Order status |
| `PRODUCTLINE` | Product category |
| `COUNTRY` | Customer country |
| `DEALSIZE` | Deal size category |

To reproduce the analysis, download the dataset from Kaggle and place it in the project folder, for example:

```text
data/Auto Sales data.csv
