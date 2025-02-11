# Global Electronics Retail Analysis (2016–2020)

## Background
Rampa Electronics retailer runs a worldwide company to sell different electronics products for its customer. Data for Rampa was provided including details on the customer and location, product, sales and store. The main goal of this project is to create an interactive dashboard using PowerBI for managers to track the overall performance of the company.

The primary objective of this project was to empower a them with deep, data-driven insights into their operations across multiple dimensions—sales, product performance, customer insights, and store performance. By integrating Power BI for data transformation, modelling and reporting, the project aimed to identify key growth opportunities, optimize resource allocation, and enhance customer satisfaction.

## Assumptions
- Delivery was done for orders that were online only and that in-store customers got their items in the stores they made their purchases.
- Given that 2021 data was incomplete with only 2 months: Jan and Feb, the data from this period was exempted from the analysis.
  
## Data Structure
These are main tables:
- Sales: Stores all transactional sales data, forming the core of revenue analysis.
- Products: Stores product details, allowing analysis of sales performance by product category etc.
- Stores: Stores information about store locations, allowing comparison between sales channels.
- Customers: Contains details of customers to support customer segmentation.
- Exchange Rates: Stores currency exchange rates to convert sales revenue into different currencies.
- Date Tables: That contains date information for orders and delivery.
![image](https://github.com/user-attachments/assets/1da4006e-51df-4e82-992f-e5ae1c148b1c)

## Key Metrics Tracked:
✔ Total Revenue: $54.14M
✔ Total Units Sold: 193,400
✔ Profit Margin: 58% ($31.55M)
✔ Average Order Value (AOV): $2,103
✔ Customer Base: 15,266
✔ In-Store vs. Online Sales: 79% In-Store, 21% Online

## Executive Summary 
Rampa Electronics Retail Analysis with records between 2016 and 2020 reveals a total revenue of $54.14M, with the United States contributing the largest share (53% -> 29M), followed by UK (13% -> 7M) and Germany (10% -> 5M), France had the least revenue contribution of 1.5M (2% of overall sales). Revenue peaked in 2019 at $18.3M before declining by 50% in 2020, likely due to the pandemic: electronic devices were not a priority purchase during that moment.

Computers (35%) and Home Appliances (20%) drove the highest sales, while USB Data Cables and Ball Bearings underperformed. In-store purchases accounted for 79% of total sales (43M), and had a higher Average Order Value (AOV) at $2,117 compared to online at $2,051.

Demographic insights show that customers aged 31-70 contributed 60% of total revenue, with the 31-50 age group generating $16.4M in sales. Revenue was evenly split between male (51%) and female (49%) customers. Most orders were made in-store.

Operational analysis indicates that average delivery times fluctuated between 3-11 days, peaking in February, July, and December, which might have led to potential customer dissatisfaction in high-demand periods.

To drive sustainable growth, the company should leverage forecasting to optimize inventory, enhance capabilities to reduce peak-season delivery delays, and expand digital marketing efforts to boost online sales conversion rates. Additionally, targeted loyalty programs for the 31-70 age group and strategies for underperforming products could maximize revenue potential.

## Visualizations
### Overview
- ![image](https://github.com/user-attachments/assets/4a2beb65-115c-47ee-9f04-605527fea51e)

### Product Performance
- ![image](https://github.com/user-attachments/assets/caca268a-10b4-4a31-b265-bc8a3f6da587)

### Customer
- ![image](https://github.com/user-attachments/assets/29ab944d-0ed8-4f4c-8f14-7c58609b81cb)

### Store Performance
- ![image](https://github.com/user-attachments/assets/80211d40-14b4-4bc5-a728-4e109282fb3e)


## Key Insights 
**1. Popular Products and Customer Locations**
Computers (35%) and Home Appliances (20%) drove the highest sales, while Games and Toys was the product category that was underperforming with sales of around 700k (1.3% of total sales).
Most Customers were from North America with most of them from United States with the least coming from Europe in France.
- ![image](https://github.com/user-attachments/assets/462a4aa9-9f27-4e31-a821-274feca193ff)
- ![image](https://github.com/user-attachments/assets/6ba0be4a-3f8c-4bf7-9d0c-5f453c6fbd86)


**2. Seasonal Trends**
- Revenue and orders had a positive correlation, when the revenue was high the number of orders was also high. Revenue and orders rose steadily and peaked at 2019 (18.3M and 9.1k orders). The months of December and February at their highest with over 7M in revenue and 3k orders while April saw a sharp decline (0.6M and 0.3k orders)
- ![image](https://github.com/user-attachments/assets/8d436ad9-41d5-474d-b8df-40cbc84a93c2)

**3. Delivery Time Optimization**
Delivery time fluctuates throughout the months, with 11 days at the highest in (February, March and June) and at the lowest in May with a waiting time of 3 days.
- ![image](https://github.com/user-attachments/assets/29484b8a-032d-460e-a9f5-1636e1c4e067)


**4. Online vs. In-Store AOV**
Instore and Online stores had quite similar AOV ($2117 and $2051) respectively.
For Online store, male customers had a slightly higher AOV ($2088) , the opposite for instore where females customer's AOV ($2123)
- ![image](https://github.com/user-attachments/assets/df7f7806-f2da-4038-88ef-8e2225ce2981)
- ![image](https://github.com/user-attachments/assets/5054b755-cac6-45b8-a9af-d0ece0b8fac9)

## Recommendations
- To improve online shopping experience to increase online conversion rates.
- To expand fulfillment centers in high demand region to stabilize delivery times and reduce shipping delays especially during prak seasons to improve customer satisfaction.
- To pair slow-moving products like cables with best-sellers: desktop PCs to increase sales efficiency.
