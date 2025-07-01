# Shofy – Beauty & Cosmetics

**Full-Stack eCommerce Web Application with Admin Dashboard**

**Shofy** is a modern and fully responsive full-stack eCommerce web application tailored for the beauty and cosmetics industry. Built with the latest web technologies including **Next.js**, **Express.js**, **MongoDB**, **Redux Toolkit**, and **Stripe**, it provides both a seamless shopping experience for users and a powerful admin panel for store management.

---

## 🚀 Tech Stack

| Frontend             | Backend    | Database | State Management          | Payment | Other Tools                   |
| -------------------- | ---------- | -------- | ------------------------- | ------- | ----------------------------- |
| Next.js + TypeScript | Express.js | MongoDB  | Redux Toolkit + RTK Query | Stripe  | Nodemailer, Sass, Bootstrap 5 |

---

## 🎯 Key Features

### 🛍️ User-Facing (Client Side)

* Responsive eCommerce UI with Bootstrap 5
* Product listing with filtering (size, color), pagination, and variation swatches
* Product quick view and quantity selector
* Video gallery for product previews
* Secure checkout with Stripe integration
* Sale countdown timer for limited-time offers
* Google and email/password authentication
* User registration, login, profile update, and password reset
* Fully mobile-friendly and touch-optimized interface

### 🔧 Admin Panel

* Add, edit, and delete products
* Manage orders and customers
* View dashboard analytics
* Admin authentication and secure access

---

## 🔐 Authentication

* Google OAuth Login
* Email-based registration and login
* Forgot/reset password functionality
* Email verification via Nodemailer

---

## 🧰 Developer Features

* TypeScript support for safer, scalable development
* Modular architecture with reusable components
* Form validation with error handling
* Clean, readable codebase with comments
* Dynamic routing for SEO-friendly URLs
* Integrated with FontAwesome and Google Fonts

---

## 📦 Installation Guide

### Prerequisites

* Node.js ≥ 16
* MongoDB URI
* Stripe API Keys
* Google OAuth credentials
* Email credentials for Nodemailer

### Step-by-Step Setup

1. **Clone the Repositories**

   ```bash
   git clone https://github.com/Hamed-Hasan/shofy-Beauty-and-Cosmetics-ecommerce-client.git
   git clone https://github.com/Hamed-Hasan/shofy-Beauty-and-Cosmetics-ecommerce-backend.git
   ```

2. **Install Dependencies**

   **Client:**

   ```bash
   cd shofy-Beauty-and-Cosmetics-ecommerce-client
   npm install
   ```

   **Server:**

   ```bash
   cd ../shofy-Beauty-and-Cosmetics-ecommerce-backend
   npm install
   ```

3. **Environment Variables**

   Create `.env` files for both the client and server. Examples:

   **Server `.env`**

   ```
   PORT=5000
   MONGODB_URI=your_mongo_uri
   STRIPE_SECRET_KEY=your_stripe_key
   JWT_SECRET=your_jwt_secret
   EMAIL_USER=your_email
   EMAIL_PASS=your_password
   ```

4. **Build & Run**

   **Client:**

   ```bash
   npm run build
   npm run dev
   ```

   **Server:**

   ```bash
   npm start
   ```

5. **Access the Application**

   Open your browser at:

   * Client: `http://localhost:3000`
   * Server: `http://localhost:5000/api`

---


## 📚 Project Overview (For Academic Submission)

* **Project Title:** Shofy – Full Stack eCommerce Web Application
* **Domain:** Web Development / eCommerce
* **Technologies Used:** MERN Stack (MongoDB, Express.js, React.js, Node.js), Next.js, Stripe, Redux Toolkit, RTK Query
* **Developed By:** *Sahil Tiwari*
* **Purpose:** To design, develop, and deploy a modern eCommerce platform tailored for the beauty & cosmetics industry, showcasing full-stack web development proficiency.

---

## 📖 Credits

* Bootstrap 5
* Google Fonts
* FontAwesome Icons
* SwiperJS
* Stripe API
* Nodemailer
