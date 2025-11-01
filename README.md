# Amazon-Sales-Customer-Segmentation Dashboard

## 1. 🧾 Project Title / Headline

**Amazon Sales & Customer Segmentation Analysis Using Python, Excel & Power BI**

A comprehensive data analysis project utilizing Python, Excel, and Power BI to uncover insights from Amazon sales data for 2025. The project explores sales performance, order statuses, and customer behavior, focusing on identifying key sales trends, understanding cancellation patterns, and segmenting customers based on spending. These insights support data-driven strategies to optimize revenue, reduce churn, and enhance customer retention.

---

## 2. 📝 Short Description / Purpose

The goal of this project is to perform deep analysis of Amazon’s transactional sales data to uncover:
- Sales trends by product, category, and payment method
- Order status breakdown (Completed, Cancelled, Pending)
- Customer segmentation (Top vs Regular buyers)

This supports strategic decisions in marketing, customer engagement, inventory planning, and revenue optimization.

---

## 3. 🛠️ Tech Stack

Tools and technologies used:

• 🧮 **Excel** – For basic data inspection, formatting, and column cleanup  
• 🐍 **Python (Pandas, Seaborn, Matplotlib)** – For data cleaning, transformation, EDA, and feature engineering  
• 📊 **Power BI Desktop** – For interactive business dashboards  
• 🧠 **DAX** – To compute KPIs like Avg Order Value, Total Sales  
• 📂 **Power Query Editor** – To shape and filter imported data  
• 💾 **File Formats** – `.csv`, `.ipynb`, `.pbix`

---

## 4. 📚 Data Source

An Amazon sales transaction dataset including fields like:

* `Order ID`, `Date`, `Product`, `Category`
* `Price`, `Quantity`, `Total Sales`
* `Customer Name`, `Location`, `Payment Method`, `Status`
* Enriched with: `Month`, `Year`, `Week`, and `Customer Type`

> 📌 **Excel was used** for correcting missing values, column alignments, and formatting inconsistencies.

---

## 5. ⭐ Features / Highlights

### • Business Problem

Without detailed sales insights, it's hard to optimize performance, understand customer behavior, or reduce cancellations. Businesses need visibility across all transaction types to improve decisions around marketing, support, and product supply.

---

### • Goal of the Analysis

To build a clean and interactive dashboard that:

✅ Analyzes sales by category, payment method, and status  
✅ Identifies which customers are top spenders  
✅ Reveals cancellation trends by category and payment method  
✅ Supports business planning with product and location insights  

---

### • Walkthrough of Key Components

#### 🐍 Python Script (`amazon_sales_analysis.ipynb`)

* Cleaned raw data: date formats, calculated sales, handled nulls  
* Created new columns: `Month`, `Year`, `Week`  
* Labeled `Customer Type` by tagging top spenders as `"Top"`  
* Filtered datasets by `Completed`, `Cancelled`, and `Pending`  
* Exported final cleaned dataset for Power BI  

---

#### 📊 Power BI Dashboard (`Amazon_Sales_Dashboard.pbix`)

**Dashboard Pages**

📄 **Page 1: Sales Overview**
- KPIs: Total Sales, Orders, Avg Order Value
- Sales by Category, Month, Payment Method
- Slicers: Month, Category, Payment Method

📄 **Page 2: Customer Insights**
- Sales by Customer Type
- Customer Location Map
- Top Customer Table
- Slicers: Customer Type, Location

📄 **Page 3: Order Status Analysis**
- Completed vs Cancelled vs Pending (Column Chart)
- Cancelled Sales by Category & Payment Method
- Slicers: Status, Month, Category

---

### • Business Impact & Insights

🔹 **Top 3 Customers** contributed significantly to total revenue  
🔹 **Pending & Cancelled Orders** were concentrated in certain product categories  
🔹 **Digital Wallets** were popular among top spenders  
🔹 Cancellation patterns suggested inventory or payment flow issues  

---

## 6. 📂 Files & GitHub Links

```markdown
- [📓 Python Notebook](https://github.com/shivamseth7676-hue/Amazon-Sales-Customer-Segmentation/blob/main/Sales%20Analysis.ipynb)
- [📄 Cleaned Dataset](https://github.com/shivamseth7676-hue/Amazon-Sales-Customer-Segmentation/blob/main/amazon_sales_data.csv)
- [📊 Power BI Dashboard](https://github.com/shivamseth7676-hue/Amazon-Sales-Customer-Segmentation/blob/main/Amazon%20Sales%20Dashboard.pbix)



