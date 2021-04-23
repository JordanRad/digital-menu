# Digital Menu Application


## Case - Group Project for Semester 3
The main goal of our team is to deploy a web app (Digital Menu) which can basically help every restaurant optimize its work flow and efficiency. Once a customer takes a seat in the restaurant, he/she will scan a QR code with his mobile phone. The customer is redirected to the menu of the restaurant where he can not only see the menu, but also to make an order. Another main goal in the project is splitting it into independent microservices which will communicate between each other.
The app would generally include the following: 
* Client app 
* Kitchen app 
* Admin panel app 

Client app is used by the customer. A customer can select products and after checkout the order is sent to the kitchen. Kitchen app will be designed so that the cooks can see all the orders they have to prepare for the customers. Admin panel is structured so it can modify existing records (like menu items, restaurant details, menu settings etc.) in the included microservices. 


## Used technologies

#### Backend - Java Springboot & PostgreSQL
* 8080: API - gateway
* 8081: Restaurant service
* 8082: Menu service
* 8083: Order service
* 8084: QR service
* 8085: Auth service
* 8086: Inventory service
* 8761: Discovery server
* 5432: PostgreSQL

#### Frontend - React & Material UI
* 3001: Restaurant
* 3002: Kitchen
* 3003: Admin Panel
