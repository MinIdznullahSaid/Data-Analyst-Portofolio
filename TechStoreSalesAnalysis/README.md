# TechStore Sales Dashboard Analysis

An interactive business intelligence dashboard built to analyze sales performance, product trends, regional distribution, and profitability for TechStore.

🔗 **[View Live Interactive Dashboard on Google Looker Studio](https://datastudio.google.com/reporting/5e22343c-0fd9-4b05-a274-af320678c08d)**

## 📌 Project Overview

This project delivers an interactive executive dashboard designed to track overall revenue metrics, monitor monthly sales dynamics, identify top-performing tech products, and evaluate distribution across customer segments and regions in Indonesia.

### Key Metrics Summary

* **Total Revenue (Omzet):** Rp377.30 M
* **Total Profit:** Rp47.18 M
* **Profit Margin:** 12.5%
* **Total Units Sold (Total Qty):** 30.1K units

---

## 📁 Dataset Information

> **Note:** The dataset used in this project is **dummy data** created for demonstration and analytical testing purposes. 
> 
> The dataset file is included in this repository and can be accessed directly from the **same directory/folder** as this `README.md` file.

---

## 🔑 Dashboard Features & Visualizations

1. **KPI Scorecards**
   * High-level tracking of Total Quantity, Revenue (Omzet), Net Profit, and Profit Margin percentage.

2. **Monthly Revenue Trends (`Total Penjualan Bulanan`)**
   * Time-series line chart tracking sales performance throughout the year.
   * Highlights peak sales periods (e.g., August–October) and seasonal dips.

3. **Customer Segment Breakdown (`Komposisi Penjualan per Segment`)**
   * Donut chart breakdown showing balanced customer distribution across three key channels:
     * **Consumer:** 33.5%
     * **Corporate:** 33.3%
     * **Home Office:** 33.2%

4. **Top 5 Best-Selling Products (`Top 5 Produk`)**
   * Horizontal bar chart ranking top individual products by demand/sales:
     1. Ecovacs Deebot
     2. iPhone SE 2022
     3. Xiaomi Mi Air Purifier
     4. ASUS ZenBook
     5. Motor Listrik Selis E-Max

5. **Geographic Distribution Map (`Sebaran Wilayah`)**
   * Spatial heatmap mapping customer order distribution across key Indonesian islands and provinces (Java, Sumatra, Sulawesi, Bali, etc.).

6. **Detailed Sub-Category Breakdown Table (`Tabel Rincian`)**
   * Detailed breakdown across 33 product sub-categories with metrics for quantity sold, gross revenue, and total profit.
   * **Top Sub-Categories by Volume:**
     * **EV Scooter** (Motor Listrik) — 3,881 units | Rp47.5M Revenue | Rp5.94M Profit
     * **Android Phone** (Smartphone) — 3,055 units | Rp39.3M Revenue | Rp4.95M Profit
     * **Gaming** (Laptop) — 1,872 units | Rp23.5M Revenue | Rp2.91M Profit
     * **iOS Phone** (Smartphone) — 1,347 units | Rp17.3M Revenue | Rp2.15M Profit
     * **Mirrorless** (Kamera) — 1,297 units | Rp15.9M Revenue | Rp1.98M Profit

## 🎛️ Interactive Filters & Slicers

The dashboard includes global filter controls for dynamic data exploration:

* **Province (`Provinsi`)**: Filter by specific geographical territories.
* **City (`Kota`)**: Drill down into city-level performance.
* **Product Category (`Kategori Produk`)**: Filter by technology verticals (Smartphones, Laptops, Home Appliances, EV Vehicles, etc.).
* **Date Range (`Tanggal Pembelian`)**: Custom date range selection.

## 🛠️ Tools & Technologies

* **Dashboard / BI Tool:** Looker Studio / Google Data Studio (or Power BI / Tableau)
* **Geographic Mapping:** Google Maps API Integration
* **Data Source:** E-commerce Transactional Dummy Dataset (available in repository)

## 📊 Key Business Insights

* **Balanced Customer Mix:** Sales are evenly split among Consumer, Corporate, and Home Office segments (~33% each), indicating a diversified revenue risk.
* **Core Profit Drivers:** Electric Scooters and Smartphones generate the highest overall unit volume and net profit margin.
* **Regional Concentration:** Sales activity is heavily concentrated along major urban hubs in Java and Sumatra.