# Pizza-shop-analysis

## Project Overview
This project analyzes the sales data of a pizza shop by using Microsoft Excel to uncover key insights into customer preferences, peak sales times, and the most popular pizza sizes. The goal is to help the shop optimize inventory management, enhance marketing strategies, and improve operational efficiency.

## Key Insights
1. **Popular Pizza Sizes**:
   - Large (L) pizzas are the top-selling size, followed by Medium (M) and Small (S).
   - Extra Large (XL) and Extra Extra Large (XXL) pizzas have much lower sales.

2. **Peak Sales Hours**:
   - Highest sales are from midday to early evening (12 PM to 6 PM), with 12 PM and 1 PM being the peak hours.

3. **Order Quantities**:
   - Most orders are for a single pizza, regardless of size. Larger orders are less frequent but occur occasionally.

## Recommendations
1. **Inventory Management**:
   - Increase stock of Large and Medium pizzas during peak hours.
   - Reduce or promote XL and XXL pizzas to manage inventory efficiently.

2. **Staff Scheduling**:
   - Increase staff during peak hours (12 PM - 6 PM) to handle the higher demand.
   - Adjust staffing during off-peak hours to minimize labor costs.

3. **Marketing Strategies**:
   - Offer special promotions or discounts on XL and XXL pizzas to boost sales.
   - Introduce lunch deals to maximize sales during peak midday hours.

4. **Customer Preferences**:
   - Focus on promoting single pizza orders since they are most common.
   - Introduce combo deals to encourage larger orders.


## Dashboare
(![Screenshot 2024-09-19 192605](https://github.com/user-attachments/assets/b0b1506a-bde0-4201-ac58-7b48abadaec1))

## Data Structure
The project uses four key tables for organizing and analyzing the data:

### `order_details` Table
- `order_details_id`: Unique identifier for each order detail.
- `order_id`: Links to the `orders` table.
- `pizza_id`: Links to the `pizzas` table.
- `quantity`: Number of pizzas ordered.

### `orders` Table
- `order_id`: Unique identifier for each order.
- `date`: Date the order was placed.
- `time`: Time the order was placed.

### `pizza_types` Table
- `pizza_id`: Unique identifier for each pizza type.
- `name`: Name of the pizza.
- `category`: Category (e.g., vegetarian, non-vegetarian).
- `ingredients`: Ingredients used in the pizza.

### `pizzas` Table
- `pizza_id`: Unique identifier for each pizza.
- `pizza_type_id`: Links to the `pizza_types` table.
- `size`: Size of the pizza (e.g., L, M, S, XL, XXL).
- `price`: Price of the pizza.
- ER Diagram (![Screenshot 2024-09-19 192832](https://github.com/user-attachments/assets/b67a6e97-79c8-4bef-a1e6-4da9040372e7)


### Other than Dashboard (Important table)

## Key Insights table 1

1. **Top-Selling Price Points**:
   - The highest quantity sold is at the price point of **$20.75**, with **8,891 units** sold.
   - Other significant price points include **$12** (5,744 units) and **$16.75** (4,380 units).

2. **Size Distribution**:
   - **Large (L)** pizzas dominate with **18,956 units** sold, showing a strong preference for this size.
   - **Medium (M)** and **Small (S)** sizes are also popular, with **15,635** and **14,403** units sold, respectively.
   - **XXL** pizzas have the lowest sales, at just **28 units**, indicating either low demand or limited availability.

3. **Price-Specific Size Preferences**:
   - At the price point of **$12.5**, Medium-sized pizzas are especially popular with **2,441 units** sold.
   - Large-sized pizzas perform well across multiple price points, particularly at **$20.75** (8,891 units) and **$16.75** (4,380 units).

4. **Potential Areas for Growth**:
   - The low sales of **XXL** pizzas suggest a potential area for marketing efforts or a reevaluation of this size offering.
   - Price points like **$25.5** and **$35.95** show minimal sales, suggesting these could benefit from promotional strategies.

## Recommendations

1. **Focus on Popular Price Points**:
   - Boost marketing and promotional efforts around the most popular price points, particularly **$20.75**, **$12**, and **$16.75**.
   - Consider bundling offers or providing discounts at these price points to increase sales further.

2. **Optimize Inventory for Large Pizzas**:
   - Ensure sufficient inventory levels of Large-sized pizzas to meet the high demand.
   - Explore introducing new flavors or variations in the Large size to capitalize on its popularity.

3. **Reevaluate XXL Size Offering**:
   - Investigate the reasons behind the low sales of XXL pizzas through customer surveys or focus groups.
   - Decide whether to continue offering XXL pizzas or replace them with more popular sizes or price points.

4. **Promotional Strategies for Underperforming Price Points**:
   - Implement targeted promotions or limited-time offers for underperforming price points like **$25.5** and **$35.95**.
   - Gather customer feedback to understand potential barriers to purchasing at these price points and address those concerns.



## Key Insights table 2

1. **Popular Sizes**:
   - **Large (L)** pizzas are the most popular, with **18,105** orders throughout the year.
   - **Medium (M)** and **Small (S)** pizzas follow, with **15,143** and **13,881** orders, respectively.
   - **Extra Large (XL)** and **Extra Extra Large (XXL)** pizzas have significantly lower sales, indicating lesser demand.

2. **Monthly Trends**:
   - **March** has the highest sales with **4,186** orders, followed by **July** (**4,301**) and **May** (**4,239**).
   - **September** has the lowest sales at **3,819** orders, suggesting a potential seasonal dip.
   - There is a noticeable increase in sales during the summer months (**May to August**), which could be linked to promotions or social gatherings.

3. **Order Quantities**:
   - The majority of orders consist of single pizzas.
   - Orders for 2, 3, or 4 pizzas at once are much lower, showing a strong preference for single pizza orders.

4. **Size Preferences in Multiple Orders**:
   - When multiple pizzas are ordered, **Large (L)** and **Medium (M)** sizes remain the most popular.
   - There is a consistent but low demand for **Small (S)** pizzas in multiple orders.

## Recommendations

1. **Inventory Management**:
   - Keep a higher stock of **Large (L)** and **Medium (M)** pizzas to meet demand efficiently.
   - Consider reducing the inventory of **Extra Large (XL)** and **Extra Extra Large (XXL)** pizzas or promoting them to increase sales.

2. **Promotional Strategies**:
   - Launch promotions during low-sales months such as **September** to stimulate sales.
   - Offer combo deals or discounts for multiple pizza orders to encourage larger purchases.

3. **Seasonal Campaigns**:
   - Take advantage of the higher sales during summer by running special summer promotions and introducing seasonal pizza flavors.
   - Align marketing campaigns with social events and holidays to drive up demand during peak periods.

4. **Customer Preferences**:
   - Conduct surveys or gather feedback to determine why **Extra Large (XL)** and **Extra Extra Large (XXL)** pizzas are less popular, and adjust offerings accordingly.
   - Consider introducing new pizza sizes or variations that could attract more interest from customers.


## Key Insights table 3

1. **Peak Sales Hours**:
   - The highest sales volumes occur between **12 PM and 6 PM**, with the peak at **12 PM (6,543 orders)** and **1 PM (6,203 orders)**.
   - Midday to early evening is the busiest period, with sales gradually increasing from **9 AM** and decreasing after **6 PM**.

2. **Popular Pizza Sizes**:
   - **Large (L)** pizzas are the most popular with **18,105 orders**.
   - **Medium (M)** pizzas follow with **15,143 orders**, and **Small (S)** pizzas with **13,881 orders**.
   - **Extra Large (XL)** and **XXL** pizzas have significantly lower sales, with **536** and **28** orders, respectively.

3. **Common Order Quantities**:
   - Single pizza orders dominate across all sizes, indicating a strong preference for individual pizza purchases.
   - Larger orders (quantities of 2, 3, or 4 pizzas) are less frequent.

4. **Hourly Sales Distribution**:
   - Sales start increasing from **9 AM**, peak around **12 PM**, and then gradually decrease after **6 PM**.
   - The lowest sales occur at **9 AM (4 orders)** and **11 PM (68 orders)**.

## Recommendations

1. **Inventory Management**:
   - Maintain higher stock levels of **Large** and **Medium** pizzas during peak hours (12 PM to 6 PM) to meet the high demand.
   - Consider reducing the stock of **XL** and **XXL** pizzas or promoting them to boost sales.

2. **Staff Scheduling**:
   - Increase staff during peak sales hours to efficiently handle the high order volume.
   - Reduce staff during off-peak hours (e.g., early mornings and late evenings) to optimize labor costs.

3. **Marketing Strategies**:
   - Launch special promotions or discounts for **XL** and **XXL** pizzas to increase sales.
   - Implement lunchtime promotions to leverage the high sales volume during **midday** hours.

4. **Customer Insights**:
   - Focus on single pizza orders, as they make up the majority of sales. Customize marketing efforts to cater to individual customers.
   - Introduce combo deals or family meal packages to encourage larger orders.

5. **Operational Efficiency**:
   - Streamline operations during peak hours to ensure quick and efficient service to customers.
   - Use sales data to monitor patterns and adjust inventory, staffing, and marketing strategies dynamically.


- ![Screenshot 2024-09-19 203844](https://github.com/user-attachments/assets/98210168-92fe-42bf-88d7-c1a33103b889)
![Screenshot 2024-09-19 203926](https://github.com/user-attachments/assets/0a3f8152-3e1c-45d4-914c-41747e39cce2)
![Screenshot 2024-09-19 204030](https://github.com/user-attachments/assets/0af7103f-4f61-432c-9c64-798ef2626272)
![Screenshot 2024-09-19 203756](https://github.com/user-attachments/assets/96b915db-773c-4e0c-ab8f-542ce3bd6dcd)
![Screenshot 2024-09-19 203823](https://github.com/user-attachments/assets/1ac38cfa-a1ee-4637-85d6-33b764bcb307)



## Executive Summary
This project provides a comprehensive analysis of the pizza shop’s sales data, highlighting key insights into customer preferences, peak sales times, and popular pizza sizes. By implementing the recommendations based on these insights, the pizza shop can optimize its inventory management, improve marketing strategies, and enhance overall operational efficiency. The data structure used in this project ensures a detailed and organized approach to analyzing sales patterns and customer behavior.




