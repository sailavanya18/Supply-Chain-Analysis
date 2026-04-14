# Supply Chain Diagnostic Dashboard

A Power BI-based supply chain analytics project that provides end-to-end visibility into product performance, logistics efficiency, defect management, and predictive risk analysis.

## Overview

This project analyzes a supply chain spanning:

- 3 product categories: Skincare, Haircare, and Cosmetics.
- 5 Indian cities: Bangalore, Chennai, Delhi, Kolkata, and Mumbai.
- 5 suppliers.
- 3 transport carriers.
- 3 shipping routes.

The dashboard is designed to help identify operational bottlenecks, quality issues, cost inefficiencies, and revenue improvement opportunities.

## Dashboard Pages

The report contains three main analytical pages:

1. **Products Sales Relationship**
   - Product sales by category.
   - Revenue contribution by product type.
   - Profitability waterfall analysis.
   - Inventory availability.
   - Sales vs revenue scatter analysis.

2. **Logistics Performance**
   - Lead time analysis by supplier.
   - Route and carrier performance.
   - Shipping cost analysis.
   - Defect rate analysis.
   - Location-based route cost comparison.
   - Transportation mode distribution.

3. **Prediction Risk Analysis**
   - Revenue prediction using linear regression.
   - Defect rate prediction by manufacturing cost.
   - What-if revenue uplift scenarios.
   - Supplier revenue forecasting.
   - Cost efficiency by location.
   - Inspection result summary.
   - Risk distribution analysis.

## Key Insights

- Total revenue is approximately **578K**.
- Average lead time is **16 days**.
- Average shipping cost is **2.28**.
- Average defect rate is **5.55**.
- **Skincare** is the highest revenue-generating category.
- **Supplier 1** and **Supplier 2** show the most urgent quality and lead time issues.
- **Carrier A** is generally more cost-efficient than Carrier B.
- Reducing lead time has a greater projected revenue impact than reducing defect rate.
- **Chennai** appears to be the most cost-efficient operational location.

## Strategic Recommendations

### Immediate Actions
- Address quality issues for Supplier 1 and Supplier 2.
- Resolve pending inspection backlog.
- Reduce use of expensive route-carrier combinations for routine shipments.

### Short-Term Actions
- Improve lead time performance for high-latency suppliers.
- Increase reliance on cost-efficient carriers.
- Expand inventory buffer for high-demand products like Skincare.
- Review high-cost operations in Mumbai.

### Long-Term Actions
- Build predictive models for defect risk.
- Create a supplier scorecard for quarterly reviews.
- Optimize routing and transportation mode selection.
- Evaluate regional distribution hub investments.


## Tools and Technologies
- MySQL 
- Power BI
- Data visualization
- Predictive analytics
- Supply chain reporting
- Forecasting and what-if analysis

## How to Use

1. Open the Power BI project file.
2. Load the supply chain dataset.
3. Refresh the data model if required.
4. Navigate through the three dashboard pages.
5. Use slicers and filters to explore product, supplier, carrier, and location-level trends.

## Business Value

This dashboard helps stakeholders:

- Monitor supply chain performance.
- Identify the most expensive and risky suppliers.
- Improve shipping and delivery efficiency.
- Reduce defects and inspection backlog.
- Make better decisions on routing, sourcing, and inventory planning.
