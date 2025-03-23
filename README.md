# Supply Chain Insights Dashboard

## Problem Statement:

In today’s fast-paced market, supply chains are more complex than ever juggling product availability, supplier performance, and operational efficiency is a constant challenge. Without clear, data-driven insights, businesses risk overstocking, supplier bottlenecks, and lost revenue opportunities.

This Power BI dashboard tackles those challenges head-on by transforming raw data into actionable insights across interactive reports:

#### Overview: 

A high-level snapshot of key performance indicators; stock levels, average profit, product performance, and more enabling quick health checks on the supply chain.

#### Products: 

Dive deep into product performance, stock analysis, lead times and sales trends to identify top-performing items and slow movers.

#### Suppliers: 

Evaluate supplier reliability and contribution to ensure you’re working with the best partners to keep operations running smoothly.

#### Goal: 

To empower decision-makers with real-time, visually compelling insights driving faster, smarter, and more profitable supply chain decisions.


### Steps followed 

- Step 1 : Load the dataset (CSV file) into Power BI Desktop & open Power Query Editor and enable "Column Distribution", "Column Quality", and "Column Profile" under the View tab for data profiling. Check for errors and missing values across columns.

- Step 2 : Handle missing values ensure critical metrics (e.g., costs, revenue) are accurate.

- Step 3 : Create new calculated columns or measures if needed (e.g., Profit Margin %). Rename columns for better readability.

- Step 4 : Design a custom dashboard background using PowerPoint for a sleek, professional look. Import the background into Power BI (set it as page background).

- Step 5 : 
Page 1: Overview
 - Create card visuals to display key metrics: Total Revenue, Products Sold, Total Cost, Stock Level, and Average Profit Margin %.

![Image](https://github.com/user-attachments/assets/a94e8df0-445f-4513-9a8f-175c89fa750b)

 - Add Donut Charts for revenue breakdown by Customer Demographics and Product Defect Rate by Product Type.

 - Include Bar Charts to show Revenue by Product Type, Shipping Carriers, and Revenue by SKU. Add a dropdown slicer for Year selection.

Page 2: Product Insights
 - Add Bar Charts for Order Quantities, Stock Level, and Lead Time by SKU. Create a Pie Chart to show Profit Margin % by Product Type.

 - Include a scatter plot to visualize Price vs Product Sold across different product types.

 - Use cards to display key metrics: Total Revenue, Products Sold, Stock Level, and Order Quantity.

Page 3: Supplier Insights
 - Add Pie Charts for Total Cost by Transportation Modes and Defect Rate % by Transportation Modes.

 - Create a Bar Chart to show Supplier Performance (Cost Breakdown). Display Stock Levels by Supplier in a table visual.

 - Include a map visual for Geographic Revenue Analysis by Supplier. Add slicers for Supplier and Location filtering.

Step 6 :

- Add Buttons for easy navigation between pages: Overview, Products, and Suppliers.
- Configure each button’s Action to Page Navigation and link them to the respective pages.

![Image](https://github.com/user-attachments/assets/37085655-970e-4994-bfcd-5e1a69923261)

Step 7: 

- Created Supplier and Location slicers, allowing users to filter data across all pages interactively.
- Synced slicers across the three pages for a seamless experience

![Image](https://github.com/user-attachments/assets/6873c6f4-2df9-4cfa-96ae-66a73a599649)
 
 # Overview Report 
 
![Image](https://github.com/user-attachments/assets/3b686910-d15e-4a38-a0f1-e56cf88929bf)

 # Products Report

![Image](https://github.com/user-attachments/assets/d2314694-2d0c-45b7-b286-b6f28e06abd2)

 # Suppliers Report

![Image](https://github.com/user-attachments/assets/3a061f6f-7033-430f-bbe4-d9b28c798786)


# Insights

### Overview Page :
- Total Revenue: $87.6M with an 81.96% Average Profit Margin, indicating strong profitability.

- Top Product Type: Skincare leads with $41M revenue.

- Demographics Insight: "Unknown" gender makes up 36% of revenue — explore this untapped customer segment.

- Defect Rates: Haircare shows the highest defect rate at 36.63% — worth investigating quality issues.

- Best Carrier: Carrier B drives $40M revenue — a reliable logistics partner to prioritize.

- Top Supplier: Supplier 3 has the highest profit margin at 90.48% — analyze why they outperform others.

### Products Insights : 
- High Stock Levels: 1.9M units in stock — balance supply-demand to avoid overstocking.

- Profit Margin by Product Type: Cosmetics leads with 37.24% margin, skincare follows closely at 36.74% — both lucrative segments.

- Lead Time & Sales Correlation: SKUs with shorter lead times tend to sell more — optimize production for slow-moving SKUs.

- Price vs Sales Scatterplot: Pricing doesn’t seem to strongly affect sales — explore value-based pricing strategies.

### Suppliers Insights Page :
- Top Cost Driver: Road transportation is the most expensive (31%) — explore alternative routes or bulk contracts.

- Defect Rate by Transport: Sea shipping has the highest defect rate (25.74%) — investigate handling and packaging improvements.

- Supplier Analysis: Supplier 1 handles the largest volume (607.78K units) but ranks lower in profit margin — negotiate better pricing.

- Geographic Revenue: Delhi and Mumbai dominate revenue contributions; assess why other regions lag.

## Key Recommendations:
1.  Prioritize Skincare & Cosmetics — high revenue and margins.
2.  Address Haircare Defects — fix quality issues to unlock potential.
3.  Renegotiate Supplier 1 terms — high volume should yield better rates.
4.  Optimize Transport Costs — explore cheaper, low-defect alternatives to road/sea.
5.  Expand High-Revenue Regions — double down on Mumbai/Delhi’s winning formula.
