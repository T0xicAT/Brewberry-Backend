

## Features:

- Product reviews and ratings
- Product pagination
- Product search feature
- User profile with orders
- Full featured shopping cart

- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Technology Stack:

- Node js
- Express Js
- MongoDB
- JWT
- React
- React Bootstrap


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

## Install Dependencies

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
nodemon
```



- Version: 1.0.0
- License: MIT
- Author:Avinash
