# TrailBlazer: Mountain Bike Sales Performance 
Power BI dashboard analyzing mountain bike sales (2020–2022), with insights on revenue, profit margin, orders, and return rates.
![Uploading ChatGPT Image Aug 29, 2025, 04_24_15 PM.png…]()

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
<img width="1138" height="545" alt="image" src="https://github.com/user-attachments/assets/2517f530-b259-4ad1-924b-37c41dcc092c" />
  
## Data Cleaning Process
- Removed redundant fields like GUIDs and internal system codes to streamline the dataset.              
- Addressed missing values across key tables (Customer, Product, Sales) by either imputing or excluding based on relevance.                
- Standardized data types—ensured dates, currency, and text fields were correctly formatted for analysis.              
- Unified category labels (e.g., “MTB” standardized to “Mountain Bike”) to avoid filter mismatches.
- Created calculated fields such as Profit = Sales - Cost and Average Order Value = Revenue / Orders to support core metrics.                      
## DASHBOARD

<img width="1267" height="712" alt="image" src="https://github.com/user-attachments/assets/8a527b3b-ec89-47b6-bebe-692903af6eb4" />

---
## Key Features 
•	Integrated Sales Data: Consolidated three years of data (2020–2022) into a single, reliable dataset.
•	Interactive Exploration: Dynamic slicers, filters, and visuals to analyze sales by product, region, and category.
•	Advanced Metrics: Custom DAX measures for profit margin, return rate, total cost, quantity, and revenue.
•	Geographical Analysis: Country- and continent-level insights into orders, revenue, and profitability.
•	Time Intelligence: Calendar table with monthly, quarterly, and yearly trend analysis.
•	Customer Insights: Segmentation by income level, age group, and parental status for deeper understanding.
•	Product Category Insights: Detailed analysis of Bikes, Accessories, and Clothing — including order patterns and return behavior.
•	Branded Design: Custom color palette and visuals aligned with Adventure Works’ theme and identity.

##  Key Visuals
•	Revenue Trend Line Chart – Monthly sales & profit growth.
•	Category Breakdown Donut Chart – Orders split into Accessories, Bikes, Clothing.
•	Top 10 Products Table – Revenue, Orders, Profit Margin %, Return Rate.
•	KPI Cards – At-a-glance performance metrics.
•	Interactive Filters – Year & Month slicers for flexible analysis.

##  Key Highlights
•	 Total Revenue: $24.91M (2020–2022).
•	 Profit Margin: $1.046M achieved.
•	Orders: 25K+ processed across 3 years.
•	 Revenue Growth: $0.59M in Jan 2020 → $1.83M in Jan 2022.
•	 Return Rate: Only 2.17% (high customer satisfaction).
•	 Top Product: Mountain-200 Black (Size 46) with $1.24M revenue.

## Top Insights
 #### Product Performance
•	Mountain-200 bicycle series led both in revenue and order volume.                  
•	Products with higher profit margins had fewer returns, especially in Europe.                    
#### Regional Insights
•	Europe achieved the highest sales with the lowest return rates.             
•	North America sold many Road-250 bikes but faced higher returns compared to Europe.                
 #### Category Breakdown
•	Accessories (helmets, bags, etc.) recorded the highest order volume.                  
•	Clothing had the lowest sales and the highest return rate (~4.4%).                
 #### Customer Analysis
•	Segmentation by age and income revealed clear targeting opportunities.                        
•	Middle Class and Upper Middle Class customers contributed the highest spending.                                 
 #### Time Trends
•	Sales and revenue peaked at the start and end of each year, highlighting ideal periods for promotions and campaigns.                                    

## Customer & Marketing Recommendations
 #### Customer Segmentation
•	Target High-Spending Segments: Prioritize Middle Class and Upper Middle Class customers who consistently contribute the highest revenue.         
•	Age-Based Marketing: Design campaigns tailored for 30–45 age groups, who show strong purchasing power in bike and accessory categories.           
•	Family-Oriented Offers: Leverage parental status segmentation with family bundles (e.g., adult + kids bikes, safety accessories).            
#### Marketing Strategy
•	Personalized Campaigns: Use demographic and income insights to create tailored ads and promotions that resonate with specific groups.             
•	Loyalty Programs: Reward repeat buyers with discounts, early access to new models, or exclusive bundles to strengthen retention.          
•	Cross-Selling Opportunities: Promote accessories (helmets, gloves, bags) alongside bike sales to increase average order value.          
#### Customer Experience
•	Reduce Return Rates: Provide clear sizing guides, detailed product descriptions, and improved after-sales support, especially for Clothing in North America.            
•	Omni-Channel Engagement: Ensure consistency in promotions across online and in-store channels for a seamless customer journey.
•	Customer Feedback Loop: Collect and analyze reviews/feedback to refine product design and improve service.               



