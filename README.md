## Supply Chain Performance & Operational Efficiency Analysis
  An end-to-end data analytics project focused on evaluating supply chain
performance, identifying logistics bottlenecks, improving inventory
management, and understanding the relationship between delivery speed,
cost, and customer satisfaction.

The project uses Python, SQL, and Power BI to transform supply chain
data into business insights and operational recommendations.
## Project Overview
The analysis focuses on warehouse-level supply chain performance across
locations, suppliers, and product categories. It examines inventory
availability, stockout risk, warehouse capacity, logistics costs,
delivery timelines, supplier quality, profitability, and customer
ratings.

The final dataset contains 500 records and 27 columns.
## Business Problems Addressed
- Logistics bottlenecks: Identify locations where longer delivery
  and order-cycle times are associated with lower customer ratings.
- Inventory gaps: Highlight warehouses with low stock relative to
  forecast demand and elevated stockout risk.
- Profitability and cost efficiency: Compare net profit with
  logistics and operational costs across locations.
- Warehouse utilization: Evaluate capacity utilization and
  inventory turnover by product category.
- Supplier performance: Compare supplier order-processing time and
  damaged-goods counts.
- Customer experience: Examine how shipping time relates to
  customer ratings.
  
## Tools & Technologies
  Tool                                Use
  Python (Pandas, NumPy)              Data cleaning, preprocessing, and
feature engineering

  SQL                                 Business analysis, aggregations,
filtering, and operational
investigation

  Microsoft Power BI                  Interactive dashboards, KPI
reporting, and visual analysis
DAX and Power Query                 Dashboard calculations and data
transformation
Project Workflow

# Phase 1: Data Preparation
The project documentation describes preparing and cleaning the supply
chain data before analysis, handling missing values, checking
consistency, and engineering analytical fields.

Key engineered fields include:
- Total_Logistics_Cost
- Stock_to_Demand_Ratio
- Capacity_Utilization
- Net_Profit
- Cost_Efficiency_Ratio
- Inventory_Turnover_Ratio

# Phase 2: SQL Analysis
The SQL script contains business-focused queries covering:
1. Loss and cost efficiency: Compare average net profit, total
   logistics cost, and cost-efficiency ratio by location.
2. Warehouse space and utilization: Compare average capacity
   utilization and inventory turnover by product category.
3. Stockout risk: Identify warehouses where Stock_to_Demand_Ratio
   is below 0.6 and Stockout_Risk is above 15.
4. Delivery delay impact: Compare average order-cycle time and
   customer rating for locations with longer order cycles.
5. Supplier quality: Rank suppliers using average order-processing
   time and total damaged goods.
6. Shipping-time buckets: Group shipping durations and compare
   customer ratings and order counts.
7. Warehouse outliers: Identify warehouses with average customer
   ratings below 3.0 and average shipping time above 4 days.
8. Delivery speed analysis: Compare average net profit and customer
   ratings across fast, medium, and slow shipping groups.

# Phase 3: Power BI Dashboard
The project documentation describes an interactive dashboard with
executive and operational views:
- Executive insights: Net profit, average customer rating, and
  total costs.
- Operational efficiency: Warehouse risks, inventory gaps, and
  shipping-impact analysis.
- Action plan: Recommended actions such as Replenish,
  Transfer, or No Action, based on the analysis.

# Key Insights
The following findings are stated in the project's existing
documentation:
- The "3.5 Day" rule: Customer ratings are reported to decline
  significantly when average shipping time exceeds 3.5 days.
- Inventory risk: More than 55% of warehouses were reported as
  understocked, with inventory gaps highlighted in locations such as
  Seattle and Denver.
- Logistics trade-off: Fast shipping (0--3 days) was reported to
  show higher operational losses than standard shipping, indicating a
  need to review route and delivery costs.
These are project-reported findings. Recalculate them from the supplied
dataset if you change the data, filters, or calculation logic.

# Business Recommendations
- Review routes and delivery methods where faster shipping is
  associated with higher costs or lower profitability.
- Prioritize replenishment or stock transfers for warehouses with low
  stock-to-demand ratios and high stockout-risk scores.
- Investigate warehouses with longer shipping times and low customer
  ratings.
- Work with suppliers showing higher damaged-goods counts or longer
  order-processing times.
- Review warehouse capacity utilization and inventory turnover to
  improve storage efficiency.
- Use the dashboard's action-plan categories to support
  warehouse-level operational decisions.
---

<img width="1322" height="745" alt="image" src="https://github.com/user-attachments/assets/3cd552be-5c4e-44bd-9697-8f34652b6703" />
<img width="1317" height="742" alt="image" src="https://github.com/user-attachments/assets/710da66a-347d-4fac-b123-ee47c0a80e57" />

