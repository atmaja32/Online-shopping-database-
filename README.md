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

1. A customer can have any number of carts.
2. A customer can make any number of payments.
3. A payment is made by exactly one customer for exactly one cart.
4. A cart can have exactly one payment made by exactly one customer.
5. An order can be shipped by exactly one shipper.
6. A shipper can ship any number of orders.
7. An order can contain any number of cart_items.
8. A cart_item can belong to exactly one order.
9. Any number of apparel can be added to cart_items, but if apparel is not in stock,
then it will not be present in cart_items.
10. Apparel must be sold by at least one retailer to be recorded in the database.
11. A retailer can sell any number of apparel.

## ER Diagram
![image](https://user-images.githubusercontent.com/37374785/215333724-a6b982ba-b1d2-40cc-a27b-a811b8dddbba.png)

## Sample user interaction
![image](https://user-images.githubusercontent.com/37374785/215333922-d55eff6f-bff7-4180-96f4-02115dc9e891.png)
