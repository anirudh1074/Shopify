
PROJECT OVERVIEW - Shopify(An E-Commerce Website) is an online shopping web application.
 
The Online Shopping is a web based application intended for online retailers & users. The main 
objective of this application is to make it interactive and its ease of use. It would make 
searching, viewing and selection of a product easier. It contains a sophisticated search 
engine for user's to search for products specific to their needs. The search engine provides 
an easy and convenient way to search for products where a user can Search for a product 
interactively and the search engine would refine the products available based on the 
user’s input. The user can then view the complete specification of each product. They can 
also view the product reviews and also write their own reviews.

It is one of a kind application which integrates all the modules and functionalities of
a shopping system on a single system that can be handled by  both administrative end and user 
end respectively.

ADMIN MODULE : Admin can login using valid credentials and perform various tasks such 
as adding products to display page and perform all the CRUD operations respectively from 
adminstrative end. Admin can also check the payment integrity and process the order accordingly.

USER / CUSTOMER  MODULE :Customer can login using their valid credentials and choose products 
among the products displayed on the web application and can read reviews ,also can write reviews.
Also can add them to cart  and proceed to place the order by
filling address and neeeded details , and pay the amount shown in the cart through payment gateway service
provided.
Users can also view the history of purchases in order section and can update their details in profile section.

# [Shopify E-Commerce Platform](https://shopify-capstone.herokuapp.com/)
A full stack ecommerce website build from scratch using MERN & redux

This project is deployed on heroku [Click to Vist and Test](https://shopify-capstone.herokuapp.com/)


## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Usage

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = your secret key
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev
# Run backend only
npm run server
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```





