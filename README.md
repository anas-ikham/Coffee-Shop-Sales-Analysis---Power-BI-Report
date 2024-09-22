# Coffee-Shop-Sales-Analysis---Power-BI-Report
## Introduction
#### This project analyzes sales data from a coffee shop using Power BI to provide insights into key performance metrics. The primary goal was to track sales performance across different products, store locations, and time periods. Metrics such as total sales, total orders, total quantities sold, and month-over-month (MoM) growth were calculated and visualized. The data was modeled using DAX (Data Analysis Expressions) to generate key insights for the business, allowing for performance tracking and decision-making
## Data Model and Key Measures
#### The data model used in the Coffee Shop Sales project revolves around a Transactions table and a Date Table to track sales and orders. The key metrics and month-over-month performance are calculated using DAX expressions in Power BI.
### Key Measures:
### 1.Total Sales:
#### This measure calculates the sum of all sales recorded in the Transactions table.
### 2.Total Orders:
#### Calculates the distinct number of orders by counting the unique transaction IDs.
### 3.Total Quantity Sold:
#### Sums the total quantity of items sold in all transactions.
### Month-to-Date (MTD) Calculations:
### 1.Current Month (CM) Sales:
#### This measure calculates the sales for the current month, allowing for month-to-date (MTD) tracking.
### 2.Current Month (CM) Orders:
#### Tracks the total number of orders for the current month.
### 3.Current Month (CM) Quantity Sold:

### Month-over-Month (MoM) Growth:
### MoM Growth & Diff Sales:
#### This calculates the month-over-month (MoM) growth for sales, showing the percentage and difference in sales volume compared to the previous month.
### MoM Growth & Diff Orders
### MoM Growth & Diff Quantity
#### These DAX measures form the foundation of the Coffee Shop Sales dashboard in Power BI, allowing for in-depth analysis of sales trends and performance across various dimensions.
## Insights:
### 1.Sales Performance:

#### Total Sales for May 2023 reached $156.73K, which is a +31.8% increase compared to the previous month. This indicates a substantial growth in overall revenue, reflecting a successful month for the coffee shop.
#### The Total Orders increased by 32.3% in the same period, adding an additional 8.2K orders, indicating higher customer activity and demand.
### 2.Sales by Store Location:

#### The top-performing store locations were:
#### Hell's Kitchen: $52.60K (a 30.5% increase)
#### Astoria: $52.43K (a 32.8% increase)
#### Lower Manhattan: $51.70K (a 32.0% increase)
#### All three stores showed strong growth, with consistent increases in sales volume. Hell’s Kitchen slightly outperformed the others, making it the top location in terms of total sales.
### 3.Product Categories:

#### Coffee was the most popular category, generating $60.36K in sales, followed by:
#### Tea: $44.54K
#### Bakery: $18.57K
#### Drinking Chocolate: $16.32K
#### Each product category saw MoM growth of over 30%, with Tea leading with a 33.5% increase. The strong performance in coffee and tea categories suggests they are core products driving revenue.
### 4.Best-Selling Products:

#### The top products were:
#### Barista Espresso: $20.42K
#### Brewed Chai Tea: $17.43K
#### Hot Chocolate: $16.32K
#### MoM growth for these products ranged from 31.3% to 35.8%, reflecting high customer demand for premium and seasonal beverages like brewed tea and hot chocolate.
### 5.Hourly Sales:

#### Sales peaked during the morning hours (7 AM - 9 AM), suggesting this is the most profitable time for the coffee shop.
#### Fridays were the most profitable day of the week, with total sales peaking at $25K, indicating increased foot traffic toward the weekend.
### Conclusion:
#### The Coffee Shop Sales analysis revealed several positive trends, particularly in overall sales growth, product performance, and store location effectiveness. The +31.8% increase in sales and the 32.3% growth in orders indicate a successful month for the business. The data highlights that customer demand for premium beverages, such as Barista Espresso and Brewed Chai Tea, is strong, and stores like Hell’s Kitchen and Astoria are critical to driving revenue.

#### The report also shows that morning sales are the most significant contributor to daily revenue, suggesting the need to prioritize staffing and inventory management during peak hours. Fridays, being the busiest day of the week, could provide opportunities for targeted promotions to capitalize on increased customer visits.
