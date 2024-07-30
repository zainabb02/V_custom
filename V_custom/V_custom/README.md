# V_custom eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

This is the course project for my MERN eCommerce course

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

##  Homepage:
![image](https://github.com/manish-thakare/V_custom/assets/82271000/820e04bd-fb4c-485a-a361-89d6523aca0a)

## Detils:
![image](https://github.com/manish-thakare/V_custom/assets/82271000/428a9131-a753-40c8-8f47-2a9b3c6d5079)

## order details:
![image](https://github.com/manish-thakare/V_custom/assets/82271000/2c176575-b9dd-492b-add0-981cf00bf80e)

## Admin view :
Checking users:
![image](https://github.com/manish-thakare/V_custom/assets/82271000/44f04bd1-3c28-479a-8b45-62a62fe2ba80)

Adding/updating product:
![image](https://github.com/manish-thakare/V_custom/assets/82271000/81d6525a-ca30-4894-bf9d-0144300738d7)

##

## Usage

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
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

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

```
