# Coffee Sales Analysis

An exploratory data analysis (EDA) project focused on analyzing coffee shop sales performance across different locations, time frames, product categories, and peak operating hours.

---

## 📌 Project Overview

This project processes and analyzes raw transaction data from a multi-location coffee shop business using **Python**, **Pandas**, **Seaborn**, and **Matplotlib**. The goal is to discover key business insights, including revenue drivers, store-by-store performance, customer purchasing behavior by hour/day, and top-performing product lines.

---

## 🔑 Key Analysis & Features

1. **Data Cleaning & Feature Engineering**
   - Verified data completeness and inspected schema structure.
   - Converted `transaction_time` to timedelta and combined it with `transaction_date` to build a unified `datetime` column.
   - Engineered new features:
     - `sales`: Total transaction revenue (`transaction_qty` × `unit_price`).
     - `day_of_week`: Day name (Monday through Sunday).
     - `hour`: Hour of the day (0–23).
     - `month`: Monthly period indexing.

2. **Sales Trends & Temporal Patterns**
   - **Daily Trends**: Line and Stacked Area plots tracking sales across time by store location.
   - **Weekly Breakdown**: Evaluated daily revenue cycles from Monday to Sunday across branches (*Astoria*, *Hell's Kitchen*, and *Lower Manhattan*).
   - **Monthly Performance**: Macro-level analysis of revenue growth across months, including specific deep-dives into targeted months (e.g., February).

3. **Product & Category Performance**
   - Sales volume and total revenue breakdown per product category.
   - Average basket size / average spend per transaction category (`avg_sales`).
   - Granular breakdown of sales by product type across individual product categories.

4. **Hourly Peak Analysis**
   - Stacked bar charts showcasing hourly customer spend by product category.
   - Comparison of peak sales hours across different store locations.

---

## 🛠️ Tech Stack & Requirements

- **Language:** Python 3.x
- **Libraries:**
  - `pandas` – Data manipulation and aggregation
  - `seaborn` – Statistical visualizations
  - `matplotlib` – Plot styling, stack plots, and layout management
  - `openpyxl` – Excel reader support for Pandas

---

## 🚀 Getting Started

### 1. Prerequisites
Install the required Python packages:

```bash
pip install pandas seaborn matplotlib openpyxl
```

### 2. Dataset Setup
Ensure your dataset file (`Coffee Shop Sales.xlsx`) is accessible or download on https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales/dataand update the file path in your script accordingly:

```python
df = pd.read_excel('path/to/Coffee Shop Sales.xlsx')
```

### 3. Execution
Run the analysis script in your favorite Python IDE (PyCharm, VS Code) or Jupyter Notebook:

```bash
python main.py
```

---

## 📊 Sample Insights Uncovered
- **Store Comparison**: Tracks individual performance across *Astoria*, *Hell's Kitchen*, and *Lower Manhattan*.
- **Peak Hours**: Highlights core operational windows where sales reach maximum throughput.
- **Product Mix**: Identifies highest-revenue product types within each major category.