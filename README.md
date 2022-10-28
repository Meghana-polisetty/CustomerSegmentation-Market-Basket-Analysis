1_DHfQvlMVBaJCHpYmj1kmCw
Customer-Segmentation-and-Market-Basket-Analysis-
Analyzed 3M+ grocery orders data from more 200k+ users to increase profitability by leveraging customer transaction behavior and purchasing history and discovered hidden association rules between products for better cross-selling and upselling.

Introduction
Instacart is an American company that operates a grocery delivery and pick-up service in the United States and Canada. The company offers its services via a website and mobile app. The service allows customers to order groceries from participating retailers with the shopping being done by a personal shopper.

With the large customer base, the company collects data of the users’ transactions behaviour and purchasing history.

The objective of this study is to increase profitability by tailoring suitable marketing approach and find key driver to used as a lever to improve profit.

The dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users.

Dataset: https://www.kaggle.com/c/instacart-market-basket-analysis

Screen Shot 2022-10-28 at 1 26 09 PM

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
Screen Shot 2022-10-28 at 1 53 14 PM

Screen Shot 2022-10-28 at 1 53 40 PM

Exploratory Data Analysis using Python
Number of Products by Department
Screen Shot 2022-10-28 at 11 49 01 AM

Personal Care and Snacks category offered the most various type of products.
Number of Products by Aisle
Screen Shot 2022-10-28 at 11 49 16 AM

Candy Chocolate aisle offered most variety types of products.
Consumer Buying Behaviour
Screen Shot 2022-10-28 at 11 49 29 AM

Most orders are placed in Day 0 & 1 (Saturday and Sunday). Most people usually shopping in the weekend. Tuesday and Wednesday have the least activity.
Screen Shot 2022-10-28 at 11 49 37 AM

Freqency of Orders by hours of the day
Screen Shot 2022-10-28 at 11 49 43 AM

Order starts getting busy after 8 AM.
The number of order almost constant between 9 AM till 4 PM. This is a range of busy hour.
Order start decreasing after 4 PM.
Consumer Buying Pattern
Screen Shot 2022-10-28 at 11 49 50 AM

Most Customer shop on the weekend, from 9 AM to 4 PM.
On the weekdays, most order are placed on Friday. Afternoon has less traffic because of working hours.
On Tuesday & Wednesday, there is not much activity.
Number of orders since last order
Screen Shot 2022-10-28 at 11 49 57 AM

Most people doing recurring shopping weekly or monthly.
Items per transaction
Screen Shot 2022-10-28 at 11 50 07 AM

Most people buy 1 -10 items in 1 transactions. Most frequent transaction is 5 items per order.
Number of transaction per customer
Screen Shot 2022-10-28 at 11 50 22 AM

Most user made a transaction between 3-6 transactions. It is indicated that Instacart has a problem in retaining new customer.
Orders vs Hour of day
Screen Shot 2022-10-28 at 12 32 05 PM

Most orders are placed from Early morning to midnight, and very few orders placed from midnight to early morning.
Frequently reordered product by weekly buyers
Screen Shot 2022-10-28 at 1 08 35 PM

Frequently reordered product by monthly buyes
Screen Shot 2022-10-28 at 1 08 40 PM

users with orders containing only reordered products
Screen Shot 2022-10-28 at 1 17 20 PM

User_id 99753 have 99 orders which contains only reordered items
Followed by User 26489 and 100935
