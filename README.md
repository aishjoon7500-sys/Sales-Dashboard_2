# Fashion Retail Sales Dashboard

An interactive Excel dashboard analyzing **31,047 e-commerce apparel orders**, built with PivotTables, PivotCharts, and slicers. The workbook breaks down sales performance across gender, age group, order status, product category, state, and sales channel.

## Overview

This project turns raw e-commerce order data into an interactive dashboard that answers key retail questions:

- How do sales split between men's and women's apparel, and across age groups?
- Which product categories (kurta, saree, western dress, etc.) sell the most?
- Which online marketplaces (Amazon, Flipkart, Myntra, etc.) drive the most revenue?
- What share of orders are delivered vs. cancelled, returned, or refunded?
- Which states generate the most sales?

## Dataset Schema

The `Dataset` sheet contains the following fields:

| Column | Description |
|---|---|
| `Index` | Row index |
| `Order ID` | Unique identifier for each order |
| `Cust ID` | Customer identifier |
| `Gender` | Customer gender — Men / Women |
| `Age` | Customer age |
| `Age Group` | Age bracket — Teenager, Adult, Senior |
| `Date` | Order date |
| `Month` | Order month (derived from date) |
| `Status` | Order status — Delivered, Cancelled, Returned, Refunded |
| `Channel` | Sales channel/marketplace — Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others |
| `Category` | Product category (e.g., Kurta, Saree, Western Dress, Ethnic Dress, Top, Set) |
| `Size` | Product size |
| `Qty` | Quantity ordered |
| `Price` | Unit price |
| `Sales` | Total sales value (`Qty × Price`) |
| `City` | Customer city |
| `State` | Customer state |
| `ship-postal-code` | Shipping postal code |

## Key Figures

- **Total Sales:** ₹21,441,209
- **Total Orders:** 31,047
- **Gender split:** Women ₹13.76M vs. Men ₹7.68M
- **Order status:** 28,641 Delivered · 1,045 Returned · 844 Cancelled · 517 Refunded
- **Top category by sales:** Set (₹10.6M), followed by Kurta (₹5.07M)
- **Top channel by sales:** Amazon (₹7.6M), followed by Myntra (₹5.0M) and Flipkart (₹4.65M)

## Dashboard Features

- **12 PivotCharts** (including modern chart types) visualizing sales across gender, age group, category, state, channel, and order status
- **5 PivotTables** feeding the dashboard's charts and KPIs, built off a shared pivot cache
- **Slicers** for interactive filtering by Category and Channel

## Tools Used

- Microsoft Excel — PivotTables, PivotCharts, Slicers

## License

Feel free to use, modify, and share this dashboard for personal or educational purposes.
