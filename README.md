

# AtliQ Mart – Supply Chain Service Performance & Customer Recovery

## 📌 Project Overview

AtliQ Mart is a growing FMCG retailer operating across **Surat, Ahmedabad, and Vadodara**.

The company is facing service-level issues that are putting customer relationships and contract renewals at risk. Management needs a way to monitor whether customer orders are delivered **On-Time (OT), In-Full (IF), and On-Time & In-Full (OTIF)** against agreed service targets.

This project develops a **Supply Chain Service Control Tower** using Power BI to identify:

- Customers at high service risk
- OTIF performance gaps
- Delivery delays
- Quantity shortfalls
- City-level service performance
- Major operational failure patterns
- Areas requiring immediate recovery action

The objective is to transform operational order data into **actionable supply chain insights** that can support customer retention and service improvement.

---

## 🎯 Business Problem

AtliQ Mart is experiencing service-level failures that may lead to customer dissatisfaction and non-renewal of contracts.

Management wants to answer:

1. What is the overall OTIF performance?
2. How far is OTIF performance from the target?
3. Which cities have the largest service gaps?
4. Which customers are at the highest service risk?
5. Are failures caused mainly by late delivery or incomplete fulfillment?
6. Which products contribute most to quantity shortfalls?
7. How significant are delivery delays?
8. Where should recovery efforts be prioritized?

---

## 📊 Key Performance Indicators

| KPI |                     Result |
|---|---:|
| Total Orders             | 31,729 |
| OTIF %                   | 29.0% |
| OTIF Target              | 75.0% |
| OTIF Gap                 | -46.0 pp |
| On-Time (OT) %           | 59.0% |
| In-Full (IF) %           | 52.8% |

### Key Finding

Overall OTIF performance is **29.0%**, significantly below the **75.0% target**, resulting in a **46 percentage-point performance gap**.

This indicates a significant service reliability issue requiring customer-level and operational recovery actions.

---

## 📈 Dashboard

### Supply Chain Service Control Tower

The Power BI dashboard provides an executive-level view of service performance and recovery priorities.

### Dashboard Components

#### 1. Daily OTIF Performance vs Target
Tracks daily OTIF performance against the target to identify persistent service-level gaps.

#### 2. Customer OTIF Gap vs Target
Ranks customers based on their OTIF performance gap and highlights high-risk accounts requiring attention.

#### 3. City-wise OTIF Performance
Compares OTIF performance across Surat, Ahmedabad, and Vadodara against the customer target.

#### 4. Order Distribution by Service Performance
Breaks down orders into:

- On-Time & In-Full
- On-Time but Not In-Full
- Late but In-Full
- Late & Not In-Full

This helps identify whether service failures are driven by delivery delays, fulfillment issues, or both.

#### 5. Products Driving Quantity Shortfall
A treemap highlights products contributing most to quantity shortfalls.

This helps prioritize inventory and replenishment investigations.

#### 6. Delivery Performance Distribution
Shows the distribution of early, on-time, and delayed deliveries.

#### 7. Customer Service Risk Assessment
Provides customer-level details including:

- Total Orders
- OTIF Orders
- OTIF %
- OTIF Target
- OTIF Gap

---

## 🔎 Key Insights

### 1. OTIF performance is significantly below target

Overall OTIF is **29.0%**, compared with the target of **75.0%**.

This represents a **-46.0 percentage-point gap**, indicating a substantial service-level issue.

### 2. Both timeliness and fulfillment contribute to service failure

Overall:

- OT % = **59.0%**
- IF % = **52.8%**

The relatively low IF performance indicates that quantity fulfillment is an important contributor to OTIF failure, alongside delivery delays.

### 3. Customer performance varies significantly

Customer-level analysis shows substantial differences in OTIF performance.

Several customers have OTIF gaps greater than **30 percentage points below target**, making them priority accounts for service recovery.

### 4. Quantity shortfalls are concentrated among specific products

The product shortfall analysis shows that a limited number of products account for a significant portion of the overall quantity shortfall.

These products should be investigated for:

- Inventory availability
- Replenishment issues
- Demand planning
- Allocation problems
- Stock-out patterns

### 5. Delivery delays remain an operational concern

The delivery distribution highlights the proportion of deliveries that are:

- Early
- On-Time
- 1 day late
- 2 days late
- 3 days late

This provides an operational view of delivery reliability and helps identify opportunities to improve delivery planning.

---

## 🚨 Recovery Priorities

Based on the analysis, the recommended recovery priorities are:

### Priority 1 – Improve OTIF Performance

The overall **29% OTIF** performance is substantially below the **75% target**.

**Action:**
Focus on the major contributors to OTIF failure rather than treating all service issues equally.

### Priority 2 – Protect High-Risk Customers

Customers with the largest OTIF gaps should receive immediate attention.

**Action:**
Develop customer-specific recovery plans and monitor their OTIF performance regularly.

### Priority 3 – Reduce Quantity Shortfalls

Products with the highest quantity shortfalls should be prioritized.

**Action:**
Review inventory availability, replenishment cycles, demand forecasts, and product allocation.

### Priority 4 – Reduce Delivery Delays

Late deliveries directly reduce OTIF performance.

**Action:**
Investigate recurring delivery delays and improve dispatch, route planning, and delivery execution.

### Priority 5 – Monitor Service Performance Continuously

OTIF should be monitored at the **daily, city, customer, and product levels**.

**Action:**
Use the control tower dashboard as a recurring performance-monitoring tool rather than a one-time report.

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **Power Query** – Data transformation and preparation
- **DAX** – KPI calculations and performance measures
- **Excel** – Initial data exploration and validation

---

## 📐 Key Metrics

### On-Time %
Measures the percentage of orders delivered on or before the agreed delivery date.

### In-Full %
Measures the percentage of orders where the requested quantity was fulfilled completely.

### IF % = In-Full Orders / Total Orders

### OTIF %
Measures orders that were both delivered on-time and fulfilled completely.
OTIF % = OTIF Orders / Total Orders

### OTIF Gap
Measures the difference between actual OTIF performance and the target.
OTIF Gap = OTIF % - OTIF Target

Ex: 29.0% - 75.0% = -46.0 percentage points


💡 Business Impact
The analysis helps supply chain management move from reactive reporting to proactive service recovery.

The dashboard enables decision-makers to:
Identify customers at risk
Prioritize service recovery
Detect major OTIF gaps
Identify product-level fulfillment issues
Monitor delivery reliability
Compare performance against targets
Focus operational resources on the highest-impact problems

📌 Portfolio Highlights
This project demonstrates practical skills in:

Data cleaning and transformation
KPI development
DAX
Power BI dashboard design
Supply chain analytics
Customer risk analysis
Root-cause analysis
Performance benchmarking
Business-focused storytelling
Actionable recommendations
👤 Project Type

Portfolio Project – Data Analytics / Supply Chain Analytics

Domain: FMCG / Supply Chain
Primary Tool: Power BI
Focus: OTIF Performance, Customer Service Risk & Recovery
```text



