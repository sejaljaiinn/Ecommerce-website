# Amazona ECommerce Website
![amazona](/template/images/amazona.jpg)



# 🛒 Ecommerce Website (MERN Stack)

A full-stack ecommerce web application built using the MERN stack (MongoDB, Express, React, Node.js).  
It includes user authentication, product browsing, cart management, and order placement features.

---

## 🚀 Live Demo


---

## 🧰 Tech Stack

**Frontend:**
- React.js
- React Router
- Axios
- CSS

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB
- Mongoose

**Authentication:**
- JWT (JSON Web Tokens)
- Bcrypt.js

---

## ✨ Features

- User registration and login
- JWT-based authentication
- Browse products
- View product details
- Add/remove items from cart
- Place orders
- User profile management
- Responsive UI

---

## 📁 Project Structure
Ecommerce-website/
│
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
│
├── frontend/
│ ├── src/
│ ├── public/
│ └── package.json
│
└── README.md

---

## ⚙️ Installation & Setup

### 1. Clone the repository

git clone https://github.com/sejaljaiinn/Ecommerce-website.git

cd Ecommerce-website


### 2. Setup Backend


cd backend
npm install


Create a `.env` file in the backend folder:


MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000


Run backend:


npm run dev


---

### 3. Setup Frontend


cd frontend
npm install
npm start


---

## 🔐 Environment Variables

Create a `.env` file inside the backend folder and add:


MONGO_URI=
JWT_SECRET=
PORT=


---

## 📦 API Endpoints (Examples)

- POST /api/users/register
- POST /api/users/login
- GET /api/products
- GET /api/products/:id
- POST /api/orders

---
