# Simple Ecommerce website

## Here is the link to the live website: [Simple Ecommerce](https://simple--ecommerce.herokuapp.com/)

---

I wanted to learn more about eCommerce websites. This website started out as following a tutorial from a [Brad Traversy tutorial](https://www.udemy.com/user/brad-traversy/). After finishing his tutorial and my background as a supply chain manager, I added on to this web site.

### Features

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

---

### Running development

- Git clone
- cd to the file location
- npm install
- cd client
- npm install
- cd ..

- add a env file with the env variables listed below
- change the database env variables to your connections
- npm data:import will seed the database
- npm data:destroy will delete all data in the database

- npm run dev
- backend server will run on port 5000
- frontend server will run on port 3000

### env variables

- NODE_ENV = development
- PORT = 5000
- MONGO_URI = your mongodb uri
- JWT_SECRET = 'abc123'
- PAYPAL_CLIENT_ID = your paypal client id
