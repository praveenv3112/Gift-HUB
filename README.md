# GiftSupply Hub

A digital marketplace for gifts, similar to Flipkart, with web and mobile apps.

## Features

- User registration and OTP login
- Gift product listings
- Search and filter
- WhatsApp integration
- Payment gateway (Razorpay)
- Admin dashboard
- Mobile app

## Tech Stack

- Backend: Node.js, Express, MySQL, Firebase Auth, Twilio, Razorpay
- Frontend: Next.js, React
- Mobile: Flutter

## Setup

### Backend

1. cd backend
2. npm install
3. Set up .env with your keys
4. Run db_schema.sql in MySQL
5. npm start

### Frontend

1. cd frontend
2. npm install
3. npm run dev

### Mobile

1. cd mobile
2. flutter pub get
3. flutter run

## API Endpoints

- POST /register - Register user
- POST /verify-otp - Verify OTP
- GET /products - Get products
- POST /products - Add product (admin)
- POST /create-order - Create payment order
- POST /send-whatsapp - Send WhatsApp message
- GET /admin/dashboard - Admin dashboard