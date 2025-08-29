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

## Data Sources

The dataset is organized into **fact and dimension tables** to support analysis and reporting:            
**Fact Tables** → Sales, Internet Sales, Reseller Sales                         
**Dimension Tables** → Products, Customers, Date, Geography, Sales Territories

This star-schema structure enables efficient **data modeling, relationships, and KPI calculations** within Power BI, ensuring accurate and interactive dashboard insights.

#### Data Model (Schema)  
Here’s the schema used in the dashboard:  

## Data Cleaning Process
- Removed redundant fields like GUIDs and internal system codes to streamline the dataset.              
- Addressed missing values across key tables (Customer, Product, Sales) by either imputing or excluding based on relevance.                
- Standardized data types—ensured dates, currency, and text fields were correctly formatted for analysis.              
- Unified category labels (e.g., “MTB” standardized to “Mountain Bike”) to avoid filter mismatches.
- Created calculated fields such as Profit = Sales - Cost and Average Order Value = Revenue / Orders to support core metrics.                      
## DASHBOARD

<img width="1267" height="712" alt="image" src="https://github.com/user-attachments/assets/8a527b3b-ec89-47b6-bebe-692903af6eb4" />

#### And here’s the map view showing sales by region:

<img width="1255" height="721" alt="image" src="https://github.com/user-attachments/assets/ddafc698-78fa-430c-bd00-d52dfe6224d4" />

---
## Key Highlights
•	Revenue Growth: Consistent increase across 2020–2022, peaking at $1.83M in Jan 2022.                   
•	Profitability: Strong profit margin of $1.046M, reflecting efficient operations.                             
•	Top-Selling Products: Mountain bikes dominate sales, with Mountain-200 Black (Size 46) leading at $1.24M.                           
•	Category Performance: Accessories generate the highest order volume, followed by bikes and clothing.                          
•	Customer Returns: Low return rate of 2.17% indicates high customer satisfaction.                                 
•	Order Trends: Over 25K orders with visible seasonal spikes, especially in early and late quarters.                                        

