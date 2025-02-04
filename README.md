# Gadget Heaven

Gadget Heaven is an online platform for buying and selling gadgets. It allows users to browse various categories of gadgets, view product details, leave reviews, and purchase items directly from the platform. This project aims to provide a seamless shopping experience for tech enthusiasts looking to explore the latest gadgets.

## Features

- **Product Catalog**: Browse through various categories of gadgets such as smartphones, laptops, accessories, and more.
- **Product Details**: View detailed information about each product including images, descriptions, prices, and reviews.
- **User Reviews**: Users can leave reviews and ratings for products they've purchased.
- **Shopping Cart**: Add products to the shopping cart and proceed to checkout.
- **Secure Authentication**: Users can sign up, log in, and manage their profiles.
- **Payment Integration**: Secure payment gateway for processing orders.
- **Order History**: Users can view and track their order history.
- **Search Functionality**: Search for products by name, category, or brand.
- **Responsive Design**: Mobile-friendly interface for a great shopping experience across all devices.

## Technologies Used

- **Frontend**: React, Tailwind CSS, Daisy UI
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Integration**: Stripe or PayPal
- **Routing**: React Router
- **State Management**: React Context API or Redux

## Installation

To get started with Gadget Heaven locally, follow these steps:

1. Clone the repository:

   ```bash
   https://github.com/kausar017/gatget-hiven.git

Navigate to the project directory:

bash
Copy
Edit
cd gadget-heaven
Install dependencies for both frontend and backend:

For frontend:

bash
Copy
Edit
cd client
npm install
For backend:

bash
Copy
Edit
cd server
npm install
Set up environment variables:

Create a .env file in the server directory and add necessary variables like MONGO_URI, JWT_SECRET, PAYMENT_SECRET_KEY, etc.
Start both frontend and backend servers:

Frontend:
bash
Copy
Edit
npm start
Backend:
bash
Copy
Edit
npm run dev
Now the app should be up and running locally at http://localhost:3000.

API Endpoints
GET /api/products: Get all products
POST /api/products: Create a new product
GET /api/products/:id: Get a specific product by ID
POST /api/products/:id/review: Add a review for a product
POST /api/auth/signup: Register a new user
POST /api/auth/login: Log in an existing user
POST /api/order: Create an order
GET /api/order/:id: Get order details
Contributing
Feel free to fork this repository, make changes, and submit a pull request.

License
This project is licensed under the MIT License.
