Star Schema Overview
The Star Schema is the simplest and most widely used architecture in Business Intelligence (BI) and data warehousing. It is characterized by a central Fact Table connected to multiple Dimension Tables, resembling a star shape.

1. The Fact Table
Definition: The central table that records quantitative data (metrics) about business processes.

Contents: Contains Foreign Keys that link to dimension tables and Measures (e.g., total_sales, quantity_sold, temperature_reading).

Granularity: Defines what a single row represents (e.g., "one sale per customer per day").

2. Dimension Tables
Definition: Tables that provide descriptive context for the data in the fact table.

Contents: Contains attributes like Date, Product_Name, Store_Location, or Customer_Segment.

De-normalization: Unlike traditional databases, dimensions are often "flat" (denormalized) to speed up read-heavy BI queries.