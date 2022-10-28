![image](https://user-images.githubusercontent.com/90289879/198733851-750ffefa-920f-4442-a318-4f58241e1368.png)

Customer-Segmentation-and-Market-Basket-Analysis-
Analyzed 3M+ grocery orders data from more 200k+ users to increase profitability by leveraging customer transaction behavior and purchasing history and discovered hidden association rules between products for better cross-selling and upselling.

Introduction
Instacart is an American company that operates a grocery delivery and pick-up service in the United States and Canada. The company offers its services via a website and mobile app. The service allows customers to order groceries from participating retailers with the shopping being done by a personal shopper.

With the large customer base, the company collects data of the users’ transactions behaviour and purchasing history.

The objective of this study is to increase profitability by tailoring suitable marketing approach and find key driver to used as a lever to improve profit.

The dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users.

Dataset: https://www.kaggle.com/c/instacart-market-basket-analysis

![image](https://user-images.githubusercontent.com/90289879/198733872-87a8a0bb-ec5f-48e2-a5e6-5854aaa8155e.png)

Business Model
Customers access Instacart’s platform via website or app. Whenever an order is placed on the platform, the so-called personal shoppers in proximity will receive a notification of the request. These shoppers are independent contractors, and they receive by delivery made. Once a shopper accepts the request, they drive to the grocery store chosen, pick up the groceries and deliver them to the customer’s address.
Revenue Stream
Commissions
Every time an item is sold through Instacart’s platform, the company receives a percentage of the price, according to the agreement made with the retailer. In some cases, Instacart even sells some products at a higher price to increase markup.
Delivery and Service Fees (Price Discrimination)
Delivery fees vary from USD 3.99 - 9.99. Because Instacart, just like other platforms, such as Uber or Lyft, charges according to the demand and external conditions (such as the weather), the so-called surge pricing. And also due to shipment scheduling. These fees are distributed between the store and Instacart. The service fees (mark-up prices) get around 5% to 10% of the purchase. Sometimes, there are additional fees, for example, when an order surpasses a certain weight threshold or when there is a bag fee.
Subscription
The company has the Instacart Express. It is a subscription service that ensures unlimited deliveries (or orders above USD 35), cheaper service fees, and no surge pricing for an annual (USD 99) or monthly fee (USD 9.99).
Advertising
Sellers and brands can advertise on the platform, for additional visibility. The price will depend on the categories and search terms. Usually, advertisers set a budget previously, to avoid overspending.
Cost Structure
Technological maintenance
Salaries
Shoppers payment
Payment processing fees
Administration and operations
Marketing
Key Customer
Users: People who don’t like shopping, elderly people, people who have a tight schedule; Users can schedule orders for a specific day and time.

Shopper: People with a smartphone and a vehicle (car or bicycle), people who love shopping, people who need an additional income.

Partner Stores: The ones that want to increase their sales, and those that want to reach out to more customers.

Value Proposition
Users: A convenient way to shop for groceries, quick delivery, vast inventory; Shoppers: Flexible working schedule, additional income, part-time work; Stores: Additional sales, increase in the number of customers.

Tableau Dahboard
![image](https://user-images.githubusercontent.com/90289879/198733918-0a7f4fab-6754-412a-a0bf-b7fb2a85d1c0.png)

![image](https://user-images.githubusercontent.com/90289879/198733942-39db2211-c451-40ad-96e6-bdea9abc9501.png)

Exploratory Data Analysis using Python
Number of Products by Department
![image](https://user-images.githubusercontent.com/90289879/198734033-073d0c26-dfa4-476b-8899-b7e071821c60.png)

Personal Care and Snacks category offered the most various type of products.
Number of Products by Aisle
![image](https://user-images.githubusercontent.com/90289879/198733991-919b85d9-8347-4537-9c0a-44bd9071f5cd.png)

Candy Chocolate aisle offered most variety types of products.
Consumer Buying Behaviour
![image](https://user-images.githubusercontent.com/90289879/198734055-0c45e506-242c-43a4-8061-93bad6f5ad0d.png)

Most orders are placed in Day 0 & 1 (Saturday and Sunday). Most people usually shopping in the weekend. Tuesday and Wednesday have the least activity.
![image](https://user-images.githubusercontent.com/90289879/198734090-46da2190-83c5-4d25-8007-d74fbc9128f7.png)

Freqency of Orders by hours of the day
![image](https://user-images.githubusercontent.com/90289879/198734105-912062ef-5c2a-4b5c-b505-9d9d4000b339.png)

Order starts getting busy after 8 AM.
The number of order almost constant between 9 AM till 4 PM. This is a range of busy hour.
Order start decreasing after 4 PM.
Consumer Buying Pattern
![image](https://user-images.githubusercontent.com/90289879/198734124-1c7efae4-bc53-4a2b-85bd-ca1c2b53a044.png)

Most Customer shop on the weekend, from 9 AM to 4 PM.
On the weekdays, most order are placed on Friday. Afternoon has less traffic because of working hours.
On Tuesday & Wednesday, there is not much activity.
Number of orders since last order
![image](https://user-images.githubusercontent.com/90289879/198734143-af881c8a-a1f0-45dc-a082-1cf382652d39.png)

Most people doing recurring shopping weekly or monthly.
Items per transaction
![image](https://user-images.githubusercontent.com/90289879/198734161-a1dbe170-558d-4430-b58c-0a454e431853.png)

Most people buy 1 -10 items in 1 transactions. Most frequent transaction is 5 items per order.
Number of transaction per customer
![image](https://user-images.githubusercontent.com/90289879/198734183-96733199-bfda-4bd1-bdbc-d9fb28735620.png)

Most user made a transaction between 3-6 transactions. It is indicated that Instacart has a problem in retaining new customer.
Orders vs Hour of day
![image](https://user-images.githubusercontent.com/90289879/198734207-83a2556c-dd59-4056-9052-003b9ffbd50b.png)

Most orders are placed from Early morning to midnight, and very few orders placed from midnight to early morning.
Frequently reordered product by weekly buyers
![image](https://user-images.githubusercontent.com/90289879/198734228-090a6308-4692-437c-a10f-aaacabd2521b.png)

Frequently reordered product by monthly buyers
![image](https://user-images.githubusercontent.com/90289879/198734254-1e51efc1-fa5b-4045-8d3d-f31a19db9f03.png)

users with orders containing only reordered products
![image](https://user-images.githubusercontent.com/90289879/198734286-260b70a0-da31-41db-9213-f58322d084ed.png)

User_id 99753 have 99 orders which contains only reordered items
Followed by User 26489 and 100935
