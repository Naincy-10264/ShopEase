# ShopEase

ShopEase is a full-stack e-commerce application built with React, Node.js, Express, and MongoDB.

## Features

- User registration and login with JWT authentication
- Product search, filters, cart, and checkout
- Razorpay payment integration
- Order history and PDF invoices
- Admin dashboard for products and orders

## Tech Stack

- Frontend: React, Redux Toolkit, Tailwind CSS
- Backend: Node.js, Express, MongoDB, Mongoose

## Run Locally

1. Install frontend dependencies:

   ```bash
   cd frontend
   npm install
   npm start
   ```

2. In another terminal, install and start the backend:

   ```bash
   cd backend
   npm install
   npm run dev
   ```

3. Copy the example environment files before starting:

   ```bash
   copy backend\\.env.example backend\\.env
   copy frontend\\.env.example frontend\\.env
   ```

   Add your MongoDB Atlas and Razorpay credentials to `backend/.env`.

The frontend runs on `http://localhost:3000` and the API runs on `http://localhost:5000`.
