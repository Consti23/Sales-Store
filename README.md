# Sales-Store
The dataset "Sales Analysis Report" contains sales order information with various details for each order. Here's a breakdown of the columns present in the dataset:

OrderNumber: A unique identifier for each sales order.
OrderDate: The date when the order was placed.
Ship Date: The date when the order was shipped.
Customer Name Index: An index or identifier representing the customer who placed the order.
Channel: The sales channel through which the order was placed (e.g., Wholesale, Distributor, Export).
Currency Code: The currency code for the transaction (e.g., NZD, USD).
Warehouse Code: A code identifying the warehouse from which the goods were shipped.
Delivery Region Index: An index or identifier representing the region to which the order was delivered.
Product Description Index: An index or identifier representing the product ordered.
Order Quantity: The quantity of the product ordered.
Unit Selling Price: The selling price per unit of the product.
Unit Cost: The cost per unit of the product.
The dataset seems to track the sales orders, including details about the orders, customers, products, and logistics like shipping and delivery. The information is useful for analyzing sales performance, customer behavior, product popularity, and logistical efficiency across different channels and regions. ​

Based on the deeper analysis of the "Sales Analysis Report" dataset, here are some insights:

Summary Statistics for Numerical Columns:
Customer Name Index, Delivery Region Index, and Product Description Index have a wide range of values, indicating a variety of customers, delivery regions, and products involved in the sales orders.
Order Quantity varies from 5 to 12 units, with an average of about 8.46 units per order, indicating a moderate volume of products being ordered each time.
Unit Selling Price and Unit Cost show a wide range, suggesting a diverse product mix with varying pricing and cost structures.
Unique Values in Categorical Columns:
Channel: There are 3 unique sales channels, indicating multiple avenues through which sales are being made.
Currency Code: There are 5 different currencies, reflecting international transactions.
Warehouse Code: 4 unique codes suggest orders are fulfilled from multiple locations.
Missing Values:
There are no missing values in any of the columns, which is excellent for data analysis as it means the dataset is complete without any gaps in the information.

Data Types:
The dataset comprises a mix of data types, including object (for textual or categorical information), datetime64[ns] (for dates), int64 (for integer numbers), and float64 (for floating-point numbers).
This diversity in data types indicates the dataset captures a range of information from categorical to numerical, including dates, which is crucial for temporal analysis.
This dataset is well-suited for detailed analysis, including sales performance evaluation, trend analysis over time, profitability analysis, and understanding customer buying patterns across different regions, channels, and product categories
