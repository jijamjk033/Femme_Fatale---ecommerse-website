## 💄 Femme Fatale – E-commerce Web Application

Femme Fatale is a dynamic, full-featured e-commerce platform for beauty and cosmetic products. Built with Node.js, Express.js, MongoDB, and EJS templating, it supports everything from user shopping and checkout to admin product management and order tracking.
The project is hosted and Live. You can access it : https://www.femmefatale.homeserviceapp.site/

## ✨ Key Features

## 🛍️ Customer Side

User registration & login (Token-based)

Browse products by category and search

Add to cart, wishlist, and place orders

Razorpay integration for secure payments

Order history with invoices

Email & SMS alerts using Nodemailer and Twilio

## 🛠️ Admin Panel

Admin login with dashboard

Add/edit/delete categories and products

View and manage customer orders

Coupon management

Update delivery status (Pending, Shipped, Delivered, Cancelled)

## 🧰 Tech Stack

Server: Node.js, Express.js

View Engine: EJS

Database: MongoDB (with Mongoose)

Authentication: JWT and Sessions

Payment Gateway: Razorpay

File Uploads: Multer

Mail & SMS: Nodemailer, Twilio

Templating: EJS with layout support

## 🗂️ Folder Structure (Simplified)

femme-fatale/
├── config/            # Database and environment config
├── controllers/       # Route logic
├── models/            # Mongoose schemas
├── routes/            # Express routes
├── views/             # EJS templates
│   ├── user/
│   ├── admin/
│   └── partials/
├── public/            # CSS, JS, Images
├── middleware/        # Auth & role checking
├── utils/             # Mail, OTP, Razorpay helpers
├── uploads/           # Uploaded product images
├── .env
└── app.js             # Main app file

## 🚀 Getting Started

1️⃣ Clone and Install

git clone https://github.com/yourusername/femme-fatale.git
cd femme-fatale
npm install

2️⃣ Create .env file

env
PORT=3000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
TWILIO_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token

3️⃣ Run the App

npm start
Then go to:
http://localhost:3000 – for user view
http://localhost:3000/admin – for admin dashboard
