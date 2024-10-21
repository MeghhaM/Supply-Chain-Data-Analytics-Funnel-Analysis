# Supply-Chain-Data-Analytics-Funnel-Analysis
Funnel Analysis to examine the efficiency of the supply chain process by focusing on whether shipments were delivered on time, and how different factors (e.g., shipping method, warehouse, customer behavior) affect this. 
# Define the Business Problem
For this funnel analysis, we will examine the efficiency of the supply chain process by focusing on whether shipments were delivered on time, and how different factors (e.g., shipping method, warehouse, customer behavior) affect this.

Business Question:
What factors influence whether a shipment is delayed?
How can the company optimize its supply chain to reduce delays?

# Define Funnel Stages

For the funnel, we can consider the following stages:
**Order Received:** This includes all rows in the dataset.
**Shipped from Warehouse**: Analysis based on the Warehouse_block field.
**Mode of Shipment**: Analyzing the Mode_of_Shipment field (Air, Ship, Road).
**Discount Applied:** Considering the Discount_offered field to check if discounts affect delivery times.
**Reached on Time:** The Reached_on_Time_Y_N column indicates whether the shipment arrived on time.
