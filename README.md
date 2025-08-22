🏆 A Powerful & Complete Multi-Vendor E-commerce Management System with Secure Payment and Smart Shipping

✨ Key Features

✅ Comprehensive user system (Registration, Login, Email verification, Role management)

✅ Password recovery system via email ("Forgot Password" functionality)

✅ Full profile management for each user (Edit info, profile picture, password, etc.)

✅ Admin Dashboard to manage products, orders, users, and shipping

✅ Secure online payments via Stripe (credit cards, transfers, split payments)

✅ Multi-vendor management with commissions and earnings withdrawal

✅ Product reviews and rating system with analytics

✅ Inventory and order management (reserve, ship, track, cancel)

✅ Shipping integration (random distribution or manual selection)

✅ Automatic image upload and optimization using Cloudinary

✅ Advanced protection against attacks (Helmet, Rate Limiting, CSRF, XSS, SQL Injection)

✅ Email notifications via Nodemailer (order confirmations and updates)


✅ Fully integrated RESTful API with clear documentation


🔧 Tech Stack Used

Backend: Node.js + Express.js


Database: MongoDB (Mongoose)

Authentication: JWT + Cookie-based encryption

Password Recovery: Nodemailer + Secure token system

Payment: Stripe (full payments, transfers, refunds)

Cloud Storage: Cloudinary (image storage & optimization)

Security: Helmet, Rate Limiting, CSRF, XSS Clean

Email Service: Nodemailer (Gmail SMTP)

Logging & Monitoring: Morgan


🚀 Why Choose This System?

✔ Ready to deploy – Easily integrable with any frontend (React, Angular, Vue)


✔ Flexible & scalable – Modular design for easy customization

✔ Highly secure – Multiple layers of protection against common vulnerabilities

✔ Supports diverse commerce models (B2C, B2B, Multi-Vendor)

✔ Ideal for startups and medium businesses due to its strong architecture and ease of integration


💼 Use Cases

📌 E-commerce websites (selling products, books, electronics, etc.)

📌 Service marketplaces (booking appointments, digital services)

📌 Multi-vendor platforms (like Amazon, Etsy)

📌 Dropshipping systems with automated shipping management


start the server with npm start or nodemon 

.env

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your secret key
STRIPE_WEBHOOK_SECRET=your_webhook_secret_key
FRONTEND_URL=http://localhost:5173/
EMAIL = your_email@example.com
PASSWORD = password123
PORT= 5000
NODE_ENV=development
MONGO_URL= mongodb://localhost:27017/E-Commerce
JWT_SECRET=8f3b7c8dfe0192a4b3f7cd890d5a345cf24daeb9
CRYPTO_SECRET=MySuperSecureEncryptionKey2025!
STRIPE_SECRET_KEY=sk_test_51RBERk7isu6bGfNeUGq6a4Vi0xaT54BQCXW941HeFWyvQf1DAhhKMS02gwbepLHkUE9rCOOUzAjgYEcFbW1hnliw00JcmytV85
##############################################
