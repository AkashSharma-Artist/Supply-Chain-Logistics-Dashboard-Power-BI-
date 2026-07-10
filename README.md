# Supply Chain & Logistics Dashboard (Power BI)
 
A comprehensive, multi-page Power BI dashboard built to monitor and analyze 
end-to-end supply chain performance. The report covers everything from supplier 
reliability and inventory health to shipment delays and customer revenue — 
giving a 360° view of the supply chain in one interactive tool.
 
## Overview
Supply chain operations involve multiple moving parts — suppliers, inventory, 
logistics, and customers — that are often tracked in silos. This dashboard 
consolidates all of them into a single, navigable report with dedicated pages 
for each function, connected through a central Overview page and page 
navigation buttons for easy drill-down.
 
## Dashboard Structure (6 Pages)
 
| Page | Focus |
|------|-------|
| **Home** | Landing page with title and navigation entry point |
| **Overview** | High-level KPIs and summary charts across the entire supply chain |
| **Supplier** | Supplier performance — lead time, cost, quality, order volume |
| **Inventory** | Inventory & production metrics — stock levels, defect rate |
| **Shipment** | Shipment tracking — delays, carrier performance, delivery status |
| **Customer** | Customer-level revenue, discounts, and order analysis |
 
## Key Metrics (KPIs)
- Total Revenue
- Profit & Profit Margin %
- Perfect Order %
- Total Shipments & Shipment Quantity
- Total Delivered Quantity
- Order Quantity
- Inventory Value
## Page-Level Highlights
 
**Supplier Page**
- Supplier by Average Lead Time
- Supplier by Order Quantity
- Supplier by Unit Cost
- Supplier by Average Quality Score
- Country by Average Lead Time
- Unit Cost trend by Month
  
**Inventory Page**
- Defect Rate by product/category
- Production vs inventory trend (combo chart)
- Inventory movement over time
  
**Shipment Page**
- Total Delayed Shipments (by carrier and overall)
- Carrier of Delayed Shipments
- Status of Total Shipments (on-time vs delayed, donut breakdown)
- Delay trend over time
  
**Customer Page**
- Total Revenue by Customer
- Discounts analysis by customer
- Scatter plot: Discount % vs Quantity Sold vs Total Revenue
- Revenue trend (combo chart)
  
## Tech Stack
- Power BI Desktop
- DAX (custom measures: Total Revenue, Profit Margin %, Perfect Order %, etc.)
- Power Query (data transformation)
- Custom theme & icon set for consistent visual branding across pages
  
## Tools & Techniques Used
- Multi-page report design with custom page navigation buttons
- DAX measures for derived KPIs (Profit Margin %, Perfect Order %)
- Combo charts (line + column) for trend + volume analysis
- Scatter chart for multi-variable relationship analysis (discount vs revenue vs quantity)
- Custom slicers for interactive filtering
- Consistent custom theme and iconography across all report pages
  
## How to View
This is an interactive Power BI report. To explore it fully (filters, drill-downs, navigation buttons):
1. Download the `.pbix` file from this repository
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the navigation buttons on the Overview page to move between Supplier, Inventory, Shipment, and Customer views
*A static preview image is included in this repo for quick reference, but the full interactive experience requires Power BI Desktop.*
 
## Conclusion
This dashboard demonstrates the ability to design a complete, multi-page 
analytics solution rather than a single isolated chart — modeling relationships 
across suppliers, inventory, shipments, and customers, and tying them together 
with consistent navigation and branding. The use of DAX-driven KPIs (like 
Perfect Order % and Profit Margin %) shows the ability to translate raw 
transactional data into metrics that matter for supply chain decision-making. 
Overall, this project reflects strong end-to-end Power BI capability — data 
modeling, DAX, and multi-page UX design — applied to a real operational domain.
