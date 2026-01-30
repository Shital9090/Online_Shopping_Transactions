Online_Shopping_Aanalysis

![](https://triprindia.com/cdn/shop/articles/shopping-online-federprivacy.jpg?v=1521026366)

Project Overview 
Project Name: Online_Shopping_Transactions
Domain: Business Intelligence / Data Analytics / E-Commerce
Tools Used: Tableau , Excel (data cleaning & initial exploration)
Dataset:

1,000 transaction records of an online shopping platform
Key columns (inferred from your dashboards): Order ID, Order Date, Customer ID, Gender, Product Category (Beauty, Books, Clothing, Electronics, Home & Kitchen, Sports), Total Amount, Payment Mode (UPI, Credit Card, Debit Card, Net Banking, COD), Order Status (Delivered, Pending, Returned, Cancelled), and more.

Project Objective
To transform raw 1,000-row e-commerce transaction data into actionable business intelligence through interactive dashboards, enabling stakeholders to:

Understand sales performance by category, time, and trends
Analyze customer behavior, payment preferences, and gender-based spending patterns
Monitor operational health via order fulfillment and return rates
Identify top customers and high-value segments for targeted marketing and retention

Key Features & Dashboards Created

Sales Performance & Customer Insights
Category-wise revenue breakdown (Sports and Beauty leading)
Monthly sales trend (line chart) showing seasonal peaks (mid-year strong) and year-end dip
Total revenue: ₹74.8M+ | Total orders: 1,000 | Unique customers: 947
Helps spot top-performing categories and seasonal opportunities

Order Fulfillment & Payment Behavior
Order status distribution (~71% Delivered, ~15% Pending, ~6–10% Returned/Cancelled)
Payment mode usage (UPI slightly leading, closely followed by cards & COD)
Top 5 high-value customers by revenue
Average Order Value (AOV) by gender – Females show significantly higher AOV
Reveals operational efficiency, preferred digital payments, and gender-based targeting potential


Business Insights Delivered

Product Strategy: Prioritize Sports, Beauty, and Clothing; revive Electronics & Home & Kitchen in low months
Marketing: Target female customers with higher AOV via personalized promotions
Operations: High delivery rate is a strength; focus on reducing pending/returned orders
Payments: Optimize for UPI experience since it's most popular
Retention: Engage top 5 customers (high revenue concentration risk/opportunity)

Skills Demonstrated

Data cleaning & transformation
DAX calculations (total revenue, AOV, monthly trends, top N customers)
Interactive visualizations (bar, line, pie, treemap if added)
Dashboard design principles (layout, color consistency, tooltips, filters/slicers)
Storytelling with data for business decisions

Future Enhancements (you can add later)

Profit & margin analysis (if cost data added)
Customer RFM segmentation
Year-over-year comparison
Geolocation insights (if city/state data available)
Predictive trends using simple forecasting

# E-Commerce Sales Performance Dashboard

![](https://github.com/Shital9090/Online_Shopping_Transactions/blob/main/Sales%20Performance%20%26%20Customer%20Insights.png)

This dashboard provides a comprehensive overview of **sales performance**, **category-wise revenue**, **monthly trends**, and **customer insights** for an e-commerce business.

## Dashboard Overview

**Page/Dashboard 1: Sales Performance & Customer Insights**

### Key Metrics
- **Total Sales Revenue**: ₹74,825,115
- **Total Orders**: 1,000
- **Total Customers**: 947

### Main Visuals
- **Category-wise Revenue** (Horizontal Bar Chart)  
  Top performing categories:  
  - Sports  
  - Beauty  
  - Clothing  
  - Books  
  - Electronics  
  - Home & Kitchen  

- **Monthly Sales Trend** (Line Chart)  
  Shows total amount over months (Jan–Dec) with category breakdown:  
  - Peak months: February, June–August  
  - Overall declining trend toward year-end  

### Purpose
Helps stakeholders identify:
- Best-selling product categories
- Seasonal patterns in sales
- Revenue contribution by category

## Tools & Technologies
- Built with: Power BI / Tableau / Excel (Power Pivot) / Looker Studio (specify your tool)
- Data source: E-commerce orders dataset (cleaned and transformed)

## How to Use
1. Open the `.pbix` / `.twb` / dashboard file
2. Use slicers/filters for:
   - Product Category
   - Month/Quarter
   - Year (if multi-year data)
3. Hover over visuals for detailed tooltips

## Insights Highlighted
- **Sports** and **Beauty** categories dominate revenue.
- Strong performance in mid-year months (June–August).
- Opportunity to boost **Home & Kitchen** and **Electronics** in off-peak months.

## Files in Repository
- `Sales_Performance_Dashboard.pbix` (or equivalent)
- `data/ecommerce_sales.csv` (sample/anonymized data if included)
- `README.md` (this file)

## Future Improvements
- Add year-over-year (YoY) comparison
- Include profit margin by category
- Customer segmentation (RFM analysis)

Feel free to fork, contribute, or reach out with questions!


# E-Commerce Order Fulfillment & Payment Dashboard

![](https://github.com/Shital9090/Online_Shopping_Transactions/blob/main/Order%20Fulfillment%20%26%20Payment%20Behavior.png)

This dashboard analyzes **order status**, **payment modes**, **top customers**, and **gender-based order value** to understand fulfillment efficiency and customer payment behavior.

## Dashboard Overview

**Page/Dashboard 2: Order Fulfillment & Payment Behavior**

### Key Metrics
- **Order Status Distribution**:
  - Delivered: ~71.49%
  - Pending: ~14.89%
  - Returned: ~6.34%
  - Cancelled: ~9.71% (approx. values from pie chart)
- **Payment Mode Usage** (Bar/Count):
  - UPI: 209
  - Net Banking: 199
  - Debit Card: 201
  - Credit Card: 195
  - Cash on Delivery: 196
- **Top 5 Customers by Revenue**:
  - CUST89392 (highest)
  - CUST89666
  - CUST77371
  - CUST85671
  - CUST46436

### Main Visuals
- **Order Status Pie Chart** – Shows delivery success rate
- **Payment Mode Bar Chart** – Distribution of payment preferences
- **Top 5 Customers Bar Chart** – Revenue contribution
- **Average Order Value by Gender** (Bar Chart):
  - Female: Significantly higher AOV (~₹65k–75k range)
  - Male: Lower AOV

### Purpose
Helps operations & finance teams:
- Monitor delivery success and return rates
- Understand preferred payment methods (UPI & cards dominant)
- Identify high-value customers for loyalty programs
- Spot gender-based differences in spending (Females have higher AOV → potential targeting opportunity)

## Tools & Technologies
- Built with: Power BI / Tableau / similar BI tool
- Data source: Orders, Customers, Payments dataset

## How to Use
1. Load the dashboard file
2. Apply filters for:
   - Order Status
   - Payment Mode
   - Customer Gender
   - Date range
3. Drill through to customer details if implemented

## Insights Highlighted
- High delivery rate (~71%) indicates strong fulfillment.
- UPI is the most used payment method — optimize for digital payments.
- Female customers show higher average order value → consider gender-specific promotions.
- Focus retention efforts on top 5 customers (high revenue concentration).

## Files in Repository
- `Order_Fulfillment_Payment_Dashboard.pbix` (or equivalent)
- `data/orders_customers.csv` (if shared)
- `README.md` (this file)

## Future Improvements
- Add return reason analysis
- Payment mode trend over time
- Customer lifetime value (CLV) calculation
- Integration with logistics tracking

Contributions, suggestions, and stars are welcome!
