# Work with Database

The "Online Store" application has its own database that stores information about users, products, shopping cart, orders, and payment information. DBeaver was used to work with the MySQL server.  

Tasks:  
* Display information about all products  
* Display information about all products manufactured by Apple in the Phones category  
* Display product names and their prices, provided that the name contains the letters sa anywhere  
* Display product names and their prices, provided that the price is between $100 and $1000  
* Calculate the sum of all products manufactured by Samsung. The name of the table in the query result should be SAMSUNG TOTAL PRICE  
* Display the name of all products and their prices in descending order  
* Display the names of all manufacturers, provided that they do not repeat  
* Display the names of the first two product categories, so that they do not repeat  
* Display product names, provided that they consist of 12 characters and their names begin with A  
* Calculate the average price of all products. The table name in the query result should be PRODUCTS AVG PRICE  
* Using the IN operator, display the names and descriptions of products whose manufacturers are Samsung and Huawei  
* Using the UNION operator, display information about the name of the products from the products table and the order numbers from the orders table  
* Using the HAVING operator, count the number of products in each category, leaving only those categories in which the number of products is greater than 15  
* "Using the CASE operator, describe the following logic:  
* Display the company, category, price and name of the product, as well as the following text message:  
* If the company is Apple, then the console should display ""This is a product of Apple"".  
* If the company is Samsung, then the console should display ""This is a product of Samsung"".  
* If the company is Huawei, then the console should display ""This is a product of Huawei"".  
* If the company is Xiaomi, then the console should display ""This is a product of Xiaomi"".  

[Open SELECT requests for MySQL](https://github.com/Tokarevael/Database/blob/main/SELECT%20%D0%B2%20MySQL%20(1)%20(1).xlsx)

* Display your user's login, their order numbers and their cost (users and orders tables)  
* Display all order numbers, product names and their quantity (order_items and products tables)  
* Display all user logins and order numbers, regardless of whether they have an order or not (users and orders tables)  
* Display paid order numbers and the name of all products, regardless of whether the products are mentioned in paid orders (products and order_items_paid tables)  
* Using a nested query, display the names and cost of products whose product cost is greater than the cost of the product "Samsung Active 5" from the products table  

[Open JOIN requests for MySQL](https://github.com/Tokarevael/Database/blob/main/JOIN%20%D0%B2%20MySQL%20(1)%20(1).xlsx)

For NoSQL Mango DB was used.  

* Create a new qa_shop database  
* Create a card_info collection inside it  
* Create documents inside the collections that will repeat the information from the card_info table in MySQL  
* Display all id and card_type with valid statuses  
* Display all id and card_type with expiry_month greater than 6  
* Display all id and card_type with expiry_month greater than 5 and less than 11  
* Calculate the total number of cards with card_type = VISA  
* Display all information about cards with names containing the letter r
  
[Open requests for NoSQL Mango DB Compass](https://github.com/Tokarevael/Database/blob/main/MangoDB%20(1).xlsx)
