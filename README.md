# 🚴 Mountain Bike Sales Dashboard | Power BI Project

Hi there! 👋  
This is a Power BI dashboard I created to analyze **Mountain Bike Sales** using the AdventureWorks dataset (2020–2022). It includes interactive visuals, performance KPIs, and regional insights to help understand how bike sales are trending over time — and where improvements can be made.

It’s a hands-on portfolio project built to show my skills in **data visualization, DAX, and business analysis.**

---

## 🔍 What You’ll Find in This Dashboard

- 📦 **Total Orders** by product category
- 💰 **Total Revenue** and **Profit Margin (%)**
- 🔁 **Return Rate** to track product issues
- 📈 **Monthly Revenue Trends** (great for seasonality!)
- 🏆 A look at the **Top 10 products by revenue**
- 🌍 A **map view** of sales by continent and country

All the visuals are interactive with slicers for **year**, **month**, **continent**, and **product category**.

---

## 🧰 Tools Used

- **Power BI Desktop** – for all dashboard creation
- **DAX** – to calculate custom KPIs like profit margin and return rate
- **Excel / CSV** – for initial data cleanup
- **AdventureWorks** – as the main dataset (open-source)

---

## 📁 Folder Structure

mountain-bike-sales-dashboard/
├── 
│ ├── Advanture_Work_Project_final.pbix ← Main Power BI file
│
├── dataset/
│ ├── Sales Data
│ ├── Returns Data
│ ├── Product Lookup Tables
│ └── Calendar Table

│
├── assets/
│ ├── dashboard-preview.png
│ ├── sales-by-region.png
│ └── mountain-bike-sales-dashboard.pdf
│
└── README.md
---

## ✨ A Quick Look

Here’s a preview of the full dashboard:

![Dashboard Preview](assets/dashboard-preview.png)

And here’s the map view showing sales by region:

![Sales by Region](assets/sales-by-region.png)

Want to explore the full report?  
📄 [Click here to view the full dashboard as PDF](a
---

## 🧮 Sample DAX Logic

```DAX
-- Profit Margin (%)
Profit Margin % = 
DIVIDE(
    [Total Revenue] - [Total Cost], 
    [Total Revenue]
)

-- Return Rate
Return Rate = 
DIVIDE(
    SUM('Returns Data'[Return Qty]), 
    [Total Orders]
)


