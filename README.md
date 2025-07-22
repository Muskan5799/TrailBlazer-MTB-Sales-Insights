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

## 📁 Folder Structure

- `mountain-bike-sales-dashboard/`
  - 📊 `dashboard/`
    - `Mountain Bike Sales.pbix` – Final Power BI report
  - 📁 `dataset/`
    - `AdventureWorks Sales Data 2020.csv`
    - `AdventureWorks Sales Data 2021.csv`
    - `AdventureWorks Sales Data 2022.csv`
    - `AdventureWorks Returns Data.csv`
    - `AdventureWorks Product Lookup.csv`
    - `AdventureWorks Product Categories Lookup.csv`
    - `AdventureWorks Product Subcategories Lookup.csv`
    - `AdventureWorks Calendar Lookup.csv`
    - `AdventureWorks Customer Lookup.csv`
    - `AdventureWorks Territory Lookup.csv`
    - `Product Category Sales (Unpivot Demo).xlsx` – Used for practice/demo
  ---

## ✨ A Quick Look

#### Here’s a preview of the full dashboard:

<img width="1267" height="712" alt="image" src="https://github.com/user-attachments/assets/8a527b3b-ec89-47b6-bebe-692903af6eb4" />

#### And here’s the map view showing sales by region:

<img width="1255" height="721" alt="image" src="https://github.com/user-attachments/assets/ddafc698-78fa-430c-bd00-d52dfe6224d4" />

---

## 🧮 Sample DAX Logic

```DAX
-- Total Revenue
Total Revenue = SUM('AdventureWorks Sales Data 2022'[Revenue])

-- Total Orders
Total Orders = COUNTROWS('AdventureWorks Sales Data 2022')

-- Profit Margin %
Profit Margin % = 
DIVIDE(
    [Total Revenue] - SUM('AdventureWorks Sales Data 2022'[Total_Cost]), 
    [Total Revenue]
)

-- Return Rate
Return Rate = 
DIVIDE(
    SUM('AdventureWorks Returns Data'[Return Quantity]), 
    [Total Orders]
)
