# financial-analysis
## Project Overview
This project focuses on building an interactive financial dashboard to monitor the overall financial health of a company. The dashboard provides insights into revenue, profitability, cash flow, and operational efficiency using key financial KPIs.
The goal is to enable stakeholders to:
- Track performance over time
- Compare actuals vs budget
- Analyze cash flow and working capital
- Identify trends and potential risks

## Objectives
Build a monthly-level interactive dashboard in Microsoft Power BI
Enable filtering by date, region, and product/service
Track key financial metrics such as:
- Revenue
- Gross Margin %
- EBITDA %
- Net Cash

## Dataset Description
The dataset includes the following key components:
1. Financial Metrics
   - Revenue
   - Cost of Goods Sold (COGS)
   - Gross Profit
   - Operating Expenses (Opex)
2. EBITDA
   - Cash Flow
   - Cash Inflows
   - Cash Outflows
   - Net Cash
3. Sales Data
   - Product/Service
   - Region
   - Month
4. Working Capital
   - Receivables Aging (Days)
   - Payables Aging (Days)
5. Budgeting
   - Revenue Budget
   - Budget Variance (%)

### Data Modeling
A Date Table was created to enable time-based analysis.
Key Features:
- Year, Quarter, Month hierarchy
- Year-Month format for trend analysis
- Relationship established between DateTable and Dataset

### Data Cleaning 
- Ensured all date fields are properly formatted for time intelligence
- Created calculated columns for aging buckets
- Handled missing values where necessary

### Key Insights 
- Revenue showed fluctuations across months, indicating seasonal trends
- Gross Margin highlighted cost efficiency variations
- Cash flow analysis revealed periods of negative net cash
- Receivables aging indicated potential delays in collections

###  Tools Used
- Microsoft Power BI
- Data Modeling
- DAX (Data Analysis Expressions)

### Dashboard Features
1. KPI Cards
   - Total Revenue
   - Gross Margin %
   - EBITDA %
   - Net Cash

2. Revenue & Profit Trend
Line chart showing:
   - Revenue
   - Gross Profit
Monthly trend analysis
3. Budget vs Actual
   - Variance analysis (%)
   - Helps track financial performance against targets
  
4. Cash Flow Waterfall
   - Visualizes:
   - Cash Inflows
   - Cash Outflows
   - Net Cash position
   - Receivables Aging
- Categorized into buckets:
   - 0–15 days
   - 16–30 days
   - 31–45 days
   - 46–60 days
Helps monitor collection efficiency

### Interactivity
The dashboard includes:
- Date range slicer (Month / Quarter / Year)
Filters:
- Region
- Product/Service
- Drill-down capabilities for deeper insights
