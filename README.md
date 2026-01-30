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
