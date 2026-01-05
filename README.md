# 🛒 AI-Powered E-Commerce Web Application

A full-stack **AI-powered e-commerce platform** built for real-world usage.
Includes a **customer storefront**, **admin dashboard**, and a **secure backend API** for managing products, users, orders, and payments.

---

## ✨ Features

### 👤 User (Client)

* 🔐 User registration & login
* 🛍️ Product browsing by category
* 🔎 Product search & filtering
* 🛒 Shopping cart
* 💳 Secure checkout
* 📦 Order history & tracking
* 📱 Fully responsive UI

### 🧑‍💼 Admin Dashboard

* 🔑 Admin authentication
* ➕➖✏️ Product management (CRUD)
* 📦 Order management
* 👥 User management
* 📊 Dashboard overview

### ⚙️ Backend

* 🌐 RESTful APIs (Node.js & Express)
* 🔑 JWT authentication
* 🛡️ Role-based access control
* 🗄️ PostgreSQL database
* 💳 Secure payments
* 🤖 AI features using Gemini API

---

## 🧠 Tech Stack

### 🎨 Frontend

* ⚛️ React (Vite)
* 🧰 Redux Toolkit
* 🎨 Tailwind CSS
* 🔗 Axios

### 🖥️ Backend

* 🟢 Node.js
* 🚀 Express.js
* 🐘 PostgreSQL
* 🔐 JWT Authentication
* 💳 Stripe Payments
* 🤖 Gemini AI API

---

## 📁 Project Structure

```
ecommerce-web-app/
├── client/        # 🛍️ Customer-facing application
├── admin/         # 🧑‍💼 Admin dashboard
├── server/        # ⚙️ Backend API
├── .env.example
└── README.md
```

---

## 🔐 Environment Variables

Create a `.env` file inside the `server` folder:

```
PORT = INITIALIZE_YOUR_PORT

FRONTEND_URL = PASTE_YOUR_YOUR_FRONTEND_URL

DASHBOARD_URL = PASTE_YOUR_YOUR_DASHBOARD_URL

JWT_EXPIRES_IN = SET_JWT_EXPIRE_VALUE

COOKIE_EXPIRES_IN = SET_COOKIE_EXPIRE_VALUE

JWT_SECRET_KEY = PASTE_YOUR_JWT_SECRET_KEY

SMTP_SERVICE = gmail

SMTP_MAIL = PASTE_YOUR_EMAIL

SMTP_PASSWORD = PASTE_YOUR_EMAIL_APP_PASSWORD

SMTP_HOST = smtp.gmail.com

SMTP_PORT = 465

GEMINI_API_KEY = PASTE_YOUR_GEMINI_API_KEY

CLOUDINARY_CLIENT_NAME = PASTE_YOUR_CLOUDINARY_CLOUD_NAME

CLOUDINARY_CLIENT_API = PASTE_YOUR_CLOUDINARY_CLIENT_API

CLOUDINARY_CLIENT_SECRET = PASTE_YOUR_CLOUDINARY_SECRET_KEY

STRIPE_SECRET_KEY = PASTE_YOUR_STRIPE_SECRET_KEY

STRIPE_WEBHOOK_SECRET =  PASTE_YOUR_STRIPE_WEBHOOK_SECRET

STRIPE_FRONTEND_KEY = PASTE_YOUR_STRIPE_PUBLIC_KEY

DB_USER =

DB_HOST=

DB_NAME=

DB_PASSWORD=

DB_PORT=
```

---

## 🛠️ Installation & Setup

### **1️⃣ Install dependencies**

```bash
npm build
```

### **2️⃣ Run the project**

```bash
npm start
```

---

## 🔒 Authentication & Security

* 🔐 JWT-based authentication
* 🔑 Secure password handling
* 🚫 Protected admin routes
* 🛡️ Role-based middleware

---

## 💳 Payments

* 💰 Stripe payment integration
* ✅ Server-side payment verification

---

## 📄 License

📜 MIT License

---
