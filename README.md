# 📊 E-Commerce Analytics

## 🚀 Overview

## This project is an **interactive analytics** built with **Dash (Plotly, Flask)** to explore and analyze an **E-Commerce dataset (Online Retail)**.

## ⚡ Features

- **Sales Overview** – Track revenue trends, top products, and invoices over time.
- **Customer Analysis** – Identify top customers, spending distributions, and invoice patterns.
- **Product Analysis** – Discover top products by sales quantity and revenue (bar charts, treemaps).
- **Geographical Analysis** – Visualize revenue and customers by country on a world map.
- **Filters & Controls** – Filter by date range, countries, or specific customers.
- **Modern UI** – Responsive design using **Bootstrap Flatly theme**.

---

## 🛠️ Tech Stack

- **Python 3.9+**
- [Dash](https://dash.plotly.com/)
- [Plotly Express](https://plotly.com/python/plotly-express/)
- [Dash Bootstrap Components](https://dash-bootstrap-components.opensource.faculty.ai/)
- **Pandas & NumPy** for data manipulation
- **PyCountry** for country mapping

---

## 📊 Dataset Description

The dashboard is powered by the **Online Retail Dataset**, a widely used dataset in data analytics and machine learning projects.  
It contains **real-world transactional data** from a UK-based e-commerce retailer between **December 2010 and December 2011**.

### 🔹 Dataset Size & Scope

- **Rows:** ~500,000 transactions
- **Columns:** 8
- **Time Period:** 2010–2011
- **Region:** UK & International customers

### 🔹 Key Columns

| Column          | Description                                                                               |
| --------------- | ----------------------------------------------------------------------------------------- |
| **InvoiceNo**   | Unique identifier for each transaction (can represent orders, returns, or cancellations). |
| **StockCode**   | Product (item) code.                                                                      |
| **Description** | Name/description of the product.                                                          |
| **Quantity**    | Number of units purchased (negative values indicate returns).                             |
| **InvoiceDate** | Date and time of the transaction.                                                         |
| **UnitPrice**   | Price per unit of the product.                                                            |
| **CustomerID**  | Unique identifier for each customer.                                                      |
| **Country**     | Country where the customer resides.                                                       |

--



