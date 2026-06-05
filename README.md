# Superstore Sales Analysis — Power BI Dashboard

---

## 🔴 Live Interactive Dashboard
👉 [Click here to view the fully interactive dashboard](https://rebrand.ly/7dumpet)

---

## 📌 Project Overview

This project presents a comprehensive sales performance 
analysis of the Superstore Sales Dataset built using 
Microsoft Power BI.

The dataset contains transaction level sales data including:

- Order & Ship Dates
- Customer Segment & Region
- Product Category & Sub-Category
- Sales, Profit & Discount
- Shipping Mode & Duration
- City & State

The primary objective of this analysis was to evaluate:

- Year-over-year revenue and profit growth
- Regional and state level profitability
- The impact of discounting on profit margins
- Which products are driving losses
- Shipping and delivery performance trends

---

## 🗂️ Dataset Summary

| Metric | Value |
|---|---|
| Gross Revenue | $2.30M |
| Total Profit | $442.53K |
| Total Loss | -$156.131K |
| Profit Margin | 12.47% |
| Total Orders | 10K |
| Average Discount | 15.62% |
| Total Discounted Orders | 5.20K |
| Orders above 20% Discount | 1.39K |
| Average Shipping Days | 4 days |
| Date Range | 2014 - 2017 |
| Top Performing State | California |
| Best Performing Region | West |
| Loss Making States | 23 |

---

## 🧹 Data Preparation

The dataset was transformed in Power BI where the 
following steps were carried out:

- Filtered and validated all data types
- Created Profit Margin % calculated column
- Created Shipping Duration calculated column
- Created Discount Band groupings for analysis
- Built YOY measures for Revenue and Profit
- Applied conditional formatting for profit
  and loss indicators across visuals

---

## ❓ Business Problem

The business lacked a clear view of where revenue was 
being generated and where profitability was being eroded.

Specifically, the business could not answer:

1. Are we growing year over year — and are profits
   keeping pace with revenue growth?
2. Which regions and states are generating profit
   and which are generating losses?
3. How is discounting affecting profit margins
   across categories and sub-categories?
4. Which products are actively destroying
   business value?
5. How efficiently are orders being shipped
   across different ship modes?

---

## 🔍 Insight Questions Explored

1. What is the year-over-year change in Revenue
   and Profit from 2014 to 2017?
2. Which quarter drives the most revenue?
3. Which regions and states are most and
   least profitable?
4. At what discount level does the business
   start making losses?
5. Which sub-categories record the most
   loss making orders?
6. How does shipping mode affect
   delivery speed?
7. Which segment drives the most value —
   Consumer, Corporate or Home Office?

---

## 📊 Dashboard Preview

### Executive Overview
![Executive Overview](Screenshots/executive_overview.png)

### Time Analysis
![Time Analysis](Screenshots/time_analysis.png)

### State & Regional Performance
![State Regional](Screenshots/state_regional.png)

### Discount Analysis
![Discount Analysis](Screenshots/discount_analysis.png)

---

## 🧩 Dashboard Components

### 📋 Executive Overview

| Visual | Description |
|---|---|
| KPI Column | Gross Revenue, Total Loss, Total Profit, Profit Margin, Total Orders — each with YOY indicator |
| Regional Profit Distribution | Bar chart showing profit margin across all four regions |
| Which Segment Drives the Most Value | Clustered bar comparing Gross Revenue vs Gross Profit across Consumer, Corporate and Home Office |
| Profit Share by Category | Donut chart showing profit contribution by Technology, Office Supplies and Furniture |
| Monthly Revenue Trend | Line chart showing monthly revenue performance across the year |
| Which Products are Hurting the Bottom Line | Horizontal bar chart showing profit and loss by sub-category with red and green conditional formatting |
| Slicers | Region, Year |

---

### ⏱️ Time Analysis

| Visual | Description |
|---|---|
| KPI Column | Current Year Loss, Current Year Profit, Average Shipping Days, Average Discount — each with YOY indicator |
| Yearly Sales & Profit Trend | Horizontal bar chart comparing Gross Revenue and Gross Profit across all four years |
| Which Quarter Drives the Most Revenue | Bar chart showing quarterly revenue performance |
| Order Volume by Shipping Days | Bar chart showing number of orders by days before shipping |
| Revenue x Profit Yearly Trend | Dual line chart tracking monthly Revenue and Profit from 2014 to 2017 |
| Delivery Speed by Ship Mode | Bar chart showing average shipping days per ship mode |
| Slicers | Segment, Category, Region, Year |

---

### 🗺️ State & Regional Performance Analysis

| Visual | Description |
|---|---|
| KPI Column | Current Year Loss, Top Performing State, Best Performing Region, Loss Making States |
| Top 5 States by Profit | Bar chart showing highest profit generating states |
| Regional Profitability Ranking | Bar chart comparing profit across all four regions |
| Bottom 5 States by Profit | Bar chart with red conditional formatting showing highest loss making states |
| State & City Detail Table | Full breakdown of State, City, Gross Revenue, Gross Profit, Profit Margin % and Total Loss |
| Where is the Business Winning & Losing | Geographic bubble map with green and red bubbles showing profit and loss by location |
| Slicers | Category, State, Region, Year |

---

### 💸 Discount Analysis

| Visual | Description |
|---|---|
| KPI Column | Total Loss, Total Discounted Orders, Orders above 20% Discount, Average Discount |
| Discount % vs Profit Margin | Bar chart showing profit margin at each discount band from No Discount to 41%+ |
| Profit & Loss Breakdown | Waterfall style bar chart showing Gross Profit vs Total Loss at each discount level |
| Where are We Losing the Most Money | Bar chart showing number of recorded losses by sub-category |
| How does Discount Affect Profit and Loss | Scatter plot showing Discount % vs Profit Margin by category with 20% threshold line |
| Insights Panel | Written analytical summary explaining the impact of discounting on profitability |
| Slicers | Category, State, Region, Year |

---

## 🔑 Key Findings

### 1. Strong Revenue Growth but Profit is Not Keeping Pace
Revenue grew from $484K in 2014 to $733K in 2017 — 
a 51.4% increase over four years. However profit growth 
has not kept pace, confirming that rising discount 
activity is quietly eroding the gains from top line growth.

### 2. West Region Leads Profitability
The West leads all regions with a 14.94% profit margin 
while Central trails significantly at just 7.92% — nearly 
half the rate. Central's weak margin is driven by 
aggressive discounting in high volume states like Texas 
and Illinois.

### 3. Discounting Beyond 20% is Destroying Profitability
Orders with no discount average a healthy 29.51% margin. 
By the time discounts reach 21-30% that margin collapses 
to -10.05%. At 41% and above the business is losing 77 
cents on every dollar of revenue generated.

### 4. 23 States are Loss Making
Texas alone loses -$25.7K despite $170K in sales — 
a -15.1% margin. These are not low activity states. 
They are high volume markets where discount discipline 
has completely broken down.

### 5. Binders are the Biggest Loss Driver
Binders recorded 613 loss making orders — the highest 
of any sub-category — followed by Chairs at 235 and 
Tables at 203. These are high volume lines being sold 
at prices that guarantee losses.

### 6. Q4 Drives the Most Revenue
Q4 generated $878.08K in revenue — more than double Q1 
at $359.68K. The business is heavily dependent on the 
final quarter of the year.

### 7. California is the Top Performing State
California leads all states in profit contribution 
at $80.15K followed by New York at $79.07K.

---

## ⚠️ Limitations

- Dataset covers US market only — no international
  comparison possible
- Cost of goods data is not available — profit is
  calculated as Revenue minus Discount only
- The root cause of losses in specific states requires
  deeper cost and operational data to fully diagnose

---

## 🚀 Recommendations

### 1. Enforce a Hard 20% Discount Ceiling
Discounting beyond 20% is the single biggest driver 
of losses. Eliminating loss making orders entirely 
would lift net profit from $286K to $442K — a 54.5% 
improvement without a single new customer.

### 2. Investigate Central Region Discounting
Central trails all regions at 7.92% profit margin. 
A full review of discount authorisation in Texas 
and Illinois is recommended immediately.

### 3. Prioritise High Margin Sub-Categories
Copiers generate the highest profit margin. 
Increasing sales focus and stock availability 
for high margin products would improve 
overall profitability.

### 4. Address Q1 Revenue Gap
Q1 generates the lowest revenue at $359.68K compared 
to Q4 at $878.08K. Targeted promotions and sales 
initiatives in Q1 could reduce this gap significantly.

---

## 🛠️ Tools & Skills Used

Microsoft Power BI Desktop
- Data Modelling & Transformation
- DAX Measures & Calculated Columns
- YOY Revenue & Profit Analysis
- Conditional Formatting
- Discount Band Grouping Analysis
- Geographic Map Visuals
- Data Visualization & Storytelling
- Analytical Insight Writing

---

## 📝 Conclusion

This Superstore Sales Dashboard transforms raw 
transactional data into a clear, actionable view 
of business performance. The analysis reveals a 
business that is growing strongly on the top line 
but quietly losing ground on profitability through 
poor discount discipline.

The data does not make decisions but it removes 
every excuse for making bad ones.

---

## 🔗 Connect With Me
[LinkedIn](https://www.linkedin.com/posts/chidera-okpala-22417730a_powerbi-dataanalytics-datavisualization-ugcPost-7464011477541122048-3-Mf/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE6w03wBP8IkgWE3bRhE1kJdUlfQmNunzig)
