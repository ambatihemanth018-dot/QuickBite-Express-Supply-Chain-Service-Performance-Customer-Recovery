

QuickBite Express – Supply Chain Service Performance & Customer Recovery

📌 Project Overview
QuickBite Express is an FMCG retailer operating across Surat, Ahmedabad, and Vadodara. The business is experiencing service-level issues that could affect customer satisfaction and contract renewals.

This project uses Power BI to analyze order fulfillment and delivery performance through On-Time (OT), In-Full (IF), and On-Time & In-Full (OTIF) metrics.

A Supply Chain Service Control Tower was developed to help management quickly identify:

Customers with significant service-level gaps
Cities underperforming against OTIF targets
Delivery delay patterns
Products contributing to quantity shortfalls
Major service failure categories
Priority areas for operational recovery

The goal is to convert operational order data into actionable insights for improving service reliability and prioritizing customer recovery efforts.

🎯 Business Problem
QuickBite Express needs to improve service performance and protect customer relationships.

Management needs answers to key business questions:

Is the business meeting its OTIF service target?
Which customers have the largest OTIF gaps?
Which cities are underperforming?
Are service failures driven more by delivery delays or incomplete fulfillment?
Which products contribute most to quantity shortfalls?
Where are delivery delays concentrated?
Which customers and operational areas should receive immediate recovery attention?

📊 Dashboard Preview

1. Supply Chain Service Control Tower
The executive dashboard provides an overview of overall service performance, customer risk, city-level performance, daily OTIF trends, and order service categories.

2. Service Failure & Customer Recovery
The second dashboard page provides a deeper analysis of customer service risk, delivery delays, OTIF performance by customer, and products contributing to quantity shortfalls.

📈 Key Performance Indicators

KPI	                 Result
Total Orders	       31,729
OT %	               59.0%
IF %	               52.8%
OTIF %	             29.0%
OTIF Target	         75.0%
OTIF Gap	           -46.0 pp

Key Finding - Overall OTIF performance is 29.0%, compared with the 75.0% target, creating a 46 percentage-point gap.
This indicates a substantial service-level performance issue and highlights the need to prioritize both customer recovery and operational improvement.

🔎 Key Business Insights

1. OTIF performance is significantly below target
The overall OTIF rate of 29.0% is well below the 75.0% target.
This indicates that a large proportion of orders are failing to meet the required combination of timeliness and complete fulfillment.

3. Both delivery and fulfillment contribute to service failures

The overall:
OT % = 59.0%
IF % = 52.8%
OTIF % = 29.0%

The relatively low IF performance indicates that incomplete order fulfillment is an important service issue, while delivery timeliness also remains a major concern.

3. Customer service performance requires prioritization
Customer-level OTIF analysis reveals differences in service performance across accounts.
Customers with the largest negative OTIF gaps versus target should be treated as priority accounts for recovery and closer monitoring.

5. Quantity shortfalls are concentrated across products
The product shortfall analysis identifies products contributing significantly to incomplete fulfillment.

These products should be investigated for potential issues involving:
Inventory availability
Replenishment
Demand planning
Product allocation
Stock availability

5. Delivery delays affect service reliability
The delivery delay analysis shows the distribution of orders across different delivery-performance categories.
This helps identify recurring delays and provides an operational starting point for improving delivery reliability.

🚨 Recovery Priorities - The analysis translates the identified service gaps into five practical recovery priorities.

🔴 Priority 1 — Improve Overall OTIF
Problem: OTIF performance is significantly below the 75% target.

Recommended action:
Focus on the largest contributors to OTIF failure and track performance at the customer, city, and operational levels.

🟠 Priority 2 — Protect High-Risk Customers
Problem: Some customers have substantially larger OTIF gaps than others.

Recommended action:
Prioritize customers with the largest negative OTIF gaps and establish customer-specific recovery plans.

🟠 Priority 3 — Reduce Quantity Shortfalls
Problem: Certain products contribute disproportionately to incomplete fulfillment.

Recommended action:
Investigate inventory availability, replenishment, demand planning, and allocation for high-shortfall products.

🟡 Priority 4 — Reduce Delivery Delays
Problem: Late deliveries reduce the probability of achieving OTIF.

Recommended action:
Investigate recurring delivery delays and review dispatch, route planning, and delivery execution.

🟢 Priority 5 — Establish Continuous Service Monitoring
Problem: Service failures can be difficult to manage using periodic reporting alone.

Recommended action:
Use OTIF as a recurring performance indicator and monitor it across:
Daily → City → Customer → Product

📐 KPI Definitions

On-Time (OT) % - Percentage of orders delivered on or before the agreed delivery date.
OT % = On-Time Orders / Total Orders

In-Full (IF) % - Percentage of orders where the required quantity was completely fulfilled.
IF % = In-Full Orders / Total Orders

On-Time & In-Full (OTIF) % - Percentage of orders that were both delivered on time and fulfilled completely.
OTIF % = OTIF Orders / Total Orders

OTIF Gap - Difference between actual OTIF performance and the target.
OTIF Gap = OTIF % - OTIF Target

Example:
29.0% - 75.0% = -46.0 percentage points

🔄 Analysis Workflow

Operational Order Data
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
OT / IF / OTIF KPI Development
        ↓
Target Comparison
        ↓
Customer & City Analysis
        ↓
Service Failure Analysis
        ↓
Product Quantity Shortfall Analysis
        ↓
Delivery Delay Analysis
        ↓
Customer Risk Identification
        ↓
Recovery Prioritization
        ↓
Power BI Service Control Tower

💼 Business Impact
The dashboard helps transform supply chain reporting from descriptive monitoring into action-oriented service management.

It enables decision-makers to:

Identify customers requiring immediate attention
Prioritize OTIF performance gaps
Detect city-level service issues
Identify products contributing to incomplete fulfillment
Monitor delivery reliability
Compare actual performance against service targets
Focus operational improvement efforts on high-impact areas

The analysis provides a structured approach for customer service recovery and supply chain performance improvement.

🛠️ Tools & Technologies:
Tool	                    Purpose
Power BI Desktop	        Dashboard development and visualization
Power Query            	  Data cleaning and transformation
DAX	                      KPI calculations and performance measures
Excel	                    Initial data exploration and validation

📁 Project Structure
QuickBite Express-Supply-Chain-Analytics/
|
├── Screenshots/
│   ├── dashboard_overview.png
│   └── customer_recovery_analysis.png
|
├── dashboard/
│   └── QuickBite_Express_Supply_Chain.pbix
│
└── README.md

Dataset Note: The source dataset is not included in this repository. The project focuses on the analytical methodology, Power BI dashboard, KPI development, insights, and business recommendations.

⭐ Portfolio Highlights
This project demonstrates practical experience in:

Power BI dashboard development
Power Query data transformation
DAX measure development
Supply chain analytics
OT / IF / OTIF analysis
Customer service risk analysis
Performance benchmarking
Root-cause analysis
Product fulfillment analysis
Business-focused data storytelling
Translating analytics into recovery priorities

📌 Project Type
Portfolio Project | Data Analytics | Supply Chain Analytics

Domain: FMCG / Supply Chain
Primary Tool: Power BI
Focus: OTIF Performance, Customer Service Risk & Recovery
