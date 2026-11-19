# 📊 Smart Retail – Sales Performance Analysis

**DATA DASH | Problem I**

An end-to-end retail data analytics project investigating revenue growth versus declining profit margins across **1,000 sales orders, 4 cities, and 3 product categories.**

---

## 🎯 1. Problem Overview

A retail company operating across multiple cities has observed a critical business challenge: sales revenue is increasing, but overall profit margins are declining.

This project analyzes the `P1_sales_orders_data.csv` dataset to:

- Perform order-level revenue, cost, and profitability calculations.
- Evaluate city-wise and product-wise financial performance.
- Visualize revenue distribution using analytical charts.
- Provide actionable, evidence-based pricing, inventory, and marketing recommendations.

---

## 📈 2. Executive KPI Summary

| Metric | Value |
|:---|---:|
| Total Orders Analyzed | 1,000 Orders |
| Total Units Sold | 12,614 Units |
| Total Gross Revenue | ₹36,77,14,000.00 (₹36.77 Cr) |
| Total Product Cost | ₹31,68,84,000.00 (₹31.69 Cr) |
| Total Net Profit | ₹5,08,30,000.00 (₹5.08 Cr) |
| Overall Profit Margin | 13.82% |
| Top Revenue City | Ranchi |
| Top Profit Product | Laptop |
| Highest Margin Product | Mobile (14.76%) |

---

## 📊 3. Visual Insights & Performance Breakdown

### 3.1 City-Wise Performance

Ranchi leads all locations in gross revenue and total profit, while Jamshedpur achieves the highest percentage profit margin.

| City | Orders | Units Sold | Total Revenue (₹) | Total Profit (₹) | Margin |
|:---|---:|---:|---:|---:|---:|
| Ranchi | 240 | 3,272 | 9,64,24,000 | 1,33,53,500 | 13.85% |
| Jamshedpur | 264 | 3,133 | 9,33,30,000 | 1,29,39,500 | 13.86% |
| Kolkata | 252 | 3,135 | 9,09,42,000 | 1,25,11,000 | 13.76% |
| Patna | 244 | 3,074 | 8,70,18,000 | 1,20,26,000 | 13.82% |

**Key Finding:** Ranchi is the strongest city in terms of total revenue and profit. Jamshedpur has the highest profit margin.

### 3.2 Product-Wise Performance

Laptops contribute approximately 58.5% of total revenue and generate the highest absolute profit. However, Mobile products have a higher profit margin of 14.76%.

| Product | Orders | Units Sold | Total Revenue (₹) | Total Profit (₹) | Margin |
|:---|---:|---:|---:|---:|---:|
| Laptop | 348 | 4,464 | 21,50,83,000 | 2,93,13,000 | 13.63% |
| Tablet | 311 | 3,824 | 7,94,34,000 | 1,07,15,500 | 13.49% |
| Mobile | 341 | 4,326 | 7,31,97,000 | 1,08,01,500 | 14.76% |

**Key Finding:** Laptop generates the highest total profit, whereas Mobile provides the highest profit margin.

---

## 💡 4. Strategic Business Recommendations

### 💰 Pricing Strategy

- Bundle high-margin accessories and extended warranties with laptops.
- Aim to improve blended order margins from approximately 13.6% towards 16–18%.
- Apply controlled discount policies to maintain mobile product profitability.

### 📦 Inventory Strategy

- Prioritize laptop inventory in high-demand locations such as Ranchi and Jamshedpur.
- Maintain appropriate safety stock to reduce stockout risks.
- Negotiate 2–3% bulk procurement discounts with laptop suppliers.

### 📣 Marketing Strategy

- Launch targeted cross-selling campaigns.
- Promote high-margin mobile and tablet products to existing laptop customers.
- Use product-specific offers to improve overall profitability.

---

## 📁 5. Project Structure

```text
smart-retail-sales-analysis/
│
├── P1_sales_orders_data.csv
│
├── smart_retail_analysis.py
│
├── processed_sales_orders_with_profit.csv
│
├── city_wise_revenue_bar_chart.png
│
├── product_revenue_pie_chart.png
│
├── Smart_Retail_Sales_Performance_Report.docx
│
└── README.md
```

### File Description

| File Name | Description |
|:---|:---|
| P1_sales_orders_data.csv | Original dataset containing 1,000 sales orders |
| smart_retail_analysis.py | Python analysis and visualization script |
| processed_sales_orders_with_profit.csv | Order-level revenue, cost, and profit calculations |
| city_wise_revenue_bar_chart.png | City-wise revenue comparison |
| product_revenue_pie_chart.png | Product-wise revenue contribution |
| Smart_Retail_Sales_Performance_Report.docx | Complete analytical report |
| README.md | Project documentation and instructions |

---

## 🚀 6. How to Run Locally

### Step 1: Install Required Libraries

Open the VS Code terminal and execute:

```bash
pip install pandas matplotlib
```

### Step 2: Keep All Files Together

Ensure the original CSV dataset and Python script are saved in the same project folder.

### Step 3: Run the Python Script

```bash
python smart_retail_analysis.py
```

### Step 4: Generated Outputs

After successful execution, the program generates:

1. Console summary of overall KPIs.
2. City-wise revenue and profit analysis.
3. Product-wise revenue and profit analysis.
4. Processed CSV containing order-level calculations.
5. City-wise revenue bar chart.
6. Product-wise revenue pie chart.

---

## 📄 7. Conclusion

The analysis highlights the importance of evaluating profitability alongside revenue growth.

Ranchi emerges as the leading city in revenue and total profit, while Laptop is the strongest product in terms of revenue and absolute profit. Mobile products provide the highest profit margin.

By improving procurement costs, optimizing inventory, controlling discounts, and implementing targeted marketing strategies, the company can work towards sustainable profitability.

---

## 📜 8. License

Created for **DATA DASH – Problem I: Smart Retail Sales Performance Analysis**.

Open for educational and analytical reference.
