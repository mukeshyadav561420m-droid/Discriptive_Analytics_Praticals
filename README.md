# 🛒 Zepto Product Catalog & Pricing Analytics

**Descriptive Analytics | Product Pricing | Discounts | Inventory & Stock Availability**

## 📌 Project Overview

This project analyzes Zepto's product catalog to understand product assortment, pricing patterns, discounts, stock availability, and inventory value. It uses descriptive analytics to generate business insights that can support pricing decisions, inventory monitoring, and assortment planning.

**Dataset Overview:**
- Total product records: 3,732
- Total category labels: 14
- Data includes product details, MRP, selling price, discount percentage, weight, and stock availability.
- The dataset represents catalog-level information, not raw sales or order transaction data.

## 🎯 Project Objectives

- Analyze product distribution across categories.
- Compare average selling prices across categories.
- Identify categories with the highest average discounts.
- Analyze stock availability and out-of-stock rates.
- Explore selling price and product weight distributions.
- Categorize products by price and discount bands.
- Identify the highest-discount and most-expensive products.
- Estimate inventory value using MRP and selling prices.
- Identify low-stock products that may require replenishment.
- Recommend future improvements using predictive analytics.

## 📊 Key Performance Indicators (KPIs)

| Metric | Value |
|---|---:|
| Total Products | 3,732 |
| Total Categories | 14 |
| In-Stock Products | 3,279 (87.9%) |
| Out-of-Stock Products | 453 (12.1%) |
| Average Selling Price | ₹142 |
| Median Selling Price | ₹104 |
| Average Discount | 7.6% |
| Highest Average Discount | Fruits & Vegetables (15.5%) |
| Highest Out-of-Stock Rate | Biscuits (28.6%) |
| Low-Stock Products (≤3 units) | 897 (24.0%) |
| Median Product Weight | 225 g |
| Inventory Value at MRP | ₹24.93 lakh |
| Inventory Value at Selling Price | ₹22.43 lakh |
| Estimated Markdown Exposure | ₹2.50 lakh |

## 🔍 Key Insights

### 1. Product Distribution
- Cooking Essentials and Munchies are the largest category labels, with 514 products each.
- Meats, Fish & Eggs is the smallest category, with 63 products.
- Product distribution varies significantly across categories.

### 2. Pricing Analysis
- The overall average selling price is approximately ₹142.
- Personal Care and Paan Corner have the highest reported average selling price, at approximately ₹190.
- Fruits & Vegetables has the lowest reported average selling price, at approximately ₹40.
- Most products fall within the ₹50–₹150 price band.

### 3. Discount Analysis
- The overall average discount is approximately 7.6%.
- Fruits & Vegetables has the highest average discount, at approximately 15.5%.
- Home & Cleaning has the lowest average discount, at approximately 5.7%.
- The highest recorded discounts reach approximately 51%.

### 4. Stock Availability
- Approximately 87.9% of products are in stock.
- Approximately 12.1% of products are out of stock.
- Biscuits has the highest reported out-of-stock rate, at approximately 28.6%.
- A total of 897 products have three or fewer units available and may require stock monitoring.

### 5. Inventory Valuation
- Estimated inventory value at MRP is approximately ₹24.93 lakh.
- Estimated inventory value at selling price is approximately ₹22.43 lakh.
- The difference represents an estimated markdown exposure of approximately ₹2.50 lakh.
- Cooking Essentials and Munchies account for the largest reported inventory value.

### 6. Correlation Analysis
- MRP and selling price have a very strong positive correlation (r ≈ 0.97).
- Product weight has a moderate positive correlation with selling price.
- Discount percentage has a weak correlation with MRP and almost no correlation with product weight.

## 🛠️ Tools & Technologies

- **Python** – Data processing and analysis
- **Jupyter Notebook** – Exploratory data analysis
- **CSV / Excel** – Data storage and preparation
- **Data Visualization** – Charts and graphical analysis
- **MS Word / PDF** – Analytical report preparation

*Update this section if your implementation uses additional libraries or tools.*

## 📁 Project Structure

```text
Zepto-Product-Catalog-Analytics/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── zepto_catalog_analysis.ipynb
│
├── reports/
│   └── Zepto_Catalog_Report_20pg.pdf
│
├── images/
│   └── charts/
│
├── README.md
└── requirements.txt
```

*This is a suggested structure. Keep only the files and folders included in your actual repository.*

## 📈 Analysis & Visualizations

The project includes or discusses the following analyses:

- Product count by category
- Average selling price by category
- Average discount percentage by category
- Overall stock availability
- Out-of-stock rate by category
- Selling price distribution
- Product distribution by price band
- Product distribution by discount band
- MRP vs. selling price relationship
- Top 10 highest-discount products
- Top 10 most-expensive products
- Product weight distribution
- Correlation heatmap
- Inventory value by category
- Low-stock products by category
- Available quantity distribution

## ⚠️ Data Limitations

- The analysis is based on a supplied catalog snapshot.
- The dataset does not contain raw sales or order transaction data.
- Some category labels correspond to identical underlying rows, so category comparisons should be interpreted carefully.
- Inventory values are estimates based on available quantity and MRP or selling price.
- Demand forecasting and sales-performance evaluation require historical sales and transaction data.

## 🚀 Future Scope

- Develop demand forecasting models.
- Predict stock-out risks using historical inventory data.
- Analyze discount effectiveness using transaction data.
- Implement dynamic pricing analysis.
- Optimize product assortment using SKU-level performance.
- Build an interactive dashboard for real-time monitoring.
- Analyze catalog trends using historical snapshots.

## 📄 Project Report

The detailed project report includes descriptive analysis, charts, key performance indicators, business insights, and recommendations.

**Report:** `Zepto_Catalog_Report_20pg.pdf`

## 👨‍💻 Author

**Mukesh Yadav**

- Course: BCA (Data Science & Artificial Intelligence)
- Section: BCADS24

## ⭐ Conclusion

This project demonstrates how descriptive analytics can be used to understand product pricing, discount strategies, stock availability, and inventory value in a quick-commerce catalog.

The findings can help identify potential pricing opportunities, monitor low-stock products, and support inventory management decisions. Future integration of sales and transaction data could enable predictive analytics and more advanced business recommendations.

---
## 👨‍💻 Author

**Mukesh Yadav**

- 🎓 Course: BCA (Data Science & Artificial Intelligence)
- 🏫 Section: BCADS24
- 📊 Project: Zepto Product Catalog & Pricing Analytics



**If you find this project useful, consider giving the repository a ⭐ on GitHub.**
