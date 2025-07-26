# 🛒 Cartify – Full Stack eCommerce Website

**Cartify** is a powerful and scalable full-stack eCommerce application built using the **MERN stack** (MongoDB, Express.js, React, Node.js) with robust state management using **Redux Toolkit**. This project includes both user and admin functionalities, along with modern UI/UX, secure authentication, product filters, and more.

---

## 🚀 Features

- 👤 User Authentication (Login, Register)
- 🔐 JWT-based protected routes
- 🛍️ Product Listings with Pagination
- 🔎 Search by keyword
- 🎯 Filter by category, price, and rating
- 📝 Product details page with image & description
- 📦 Cart functionality
- 🧾 Order placement (backend API ready)
- 📧 Email integration (for alerts or confirmations)
- 🧠 Redux Toolkit for global state management
- 📂 Admin panel

---

## 🧰 Tech Stack

### Frontend
- React.js
- Redux Toolkit
- React Router DOM
- Axios
- React Helmet Async

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- JWT Authentication
- Nodemailer (for email services)

### Tools
- Postman (API testing)
- MongoDB Atlas or Local Mongo
- Cloudinary (optional image hosting)

---

## 📁 Project Structure

```bash
cartify/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       └── App.js
├── .env
├── package.json
└── README.md
```

## 🛠️ Installation & Setup
1. Clone the Repository
```
git clone https://github.com/Harishna-K/Cartify_E-Commerce_Website.git
cd Cartify_E-Commerce_Website
```

2. Backend Setup
```
cd backend
npm install
```

Create a .env file inside backend/ with the following:
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```
Run the server:
```
npm run dev
```

3. Frontend Setup
```
cd ../frontend
npm install
npm start
```


