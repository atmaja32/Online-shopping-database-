# Online-shopping-database
An online apparel shopping service's database querying application

## Description
The apparel shopping application intends to help the user view information about
apparels, shippers, retailers and additionally derive more insights from these tables. The
user interacts with the front end and generates the required information without having
to manually query the database. The user, in our case the admin who is incharge of the
workflow of the ecommerce service can view and monitor information about apparel,
retailers, customers, payments, shippers etc.The web based front end
makes it easier for the user to select variables from drop down columns and query the
database which has all the information about apparel, retailers, shipping, items in cart,
customer details, payments etc.

## Business Rules
The application has the following business rules:
● A customer can have any number of carts.
● A customer can make any number of payments.
● A payment is made by exactly one customer for exactly one cart.
● A cart can have exactly one payment made by exactly one customer.
● An order can be shipped by exactly one shipper.
● A shipper can ship any number of orders.
● An order can contain any number of cart_items.
● A cart_item can belong to exactly one order.
● Any number of apparel can be added to cart_items, but if apparel is not in stock,
then it will not be present in cart_items.
● Apparel must be sold by at least one retailer to be recorded in the database.
● A retailer can sell any number of apparel.

## ER Diagram
![image](https://user-images.githubusercontent.com/37374785/215333724-a6b982ba-b1d2-40cc-a27b-a811b8dddbba.png)
