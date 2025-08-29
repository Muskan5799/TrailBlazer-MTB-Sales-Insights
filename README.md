# TrailBlazer: Mountain Bike Sales Performance 
Power BI dashboard analyzing mountain bike sales (2020–2022), with insights on revenue, profit margin, orders, and return rates.

![WhatsApp Image 2025-08-29 at 11 45 16 AM](https://github.com/user-attachments/assets/49ac2a0b-8c7d-4b0f-83c0-d19761adc2fb)

 ## Overview  

This project analyzes mountain bike sales data (2020–2022) and presents it through an interactive Power BI dashboard.
It provides insights into revenue trends, profit margins, sales by category, and return rates.
The dashboard also highlights top-performing products and tracks overall business performance.
It enables stakeholders to make data-driven decisions to improve sales strategy and profitability.

## Tools & Skills

#### Tools:
•	Power BI → Data visualization & dashboard creation

•	Microsoft Excel → Data cleaning & preprocessing
#### Skills Applied:
•	Data Cleaning & Transformation

•	DAX Calculations (KPIs & Measures)

•	Data Modeling & Relationships
•	Interactive Dashboard Design
•	Sales & Profitability Analysis
•	Business Insights & Reporting

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
