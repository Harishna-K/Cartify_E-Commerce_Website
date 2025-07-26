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

## ⚙️ Setup Instructions
1️⃣ Clone the Repository
```
git clone https://github.com/Harishna-K/Cartify_E-Commerce_Website.git
cd Cartify_E-Commerce_Website
```

2️⃣ Install Root Dependencies
```
npm install
```

3️⃣ Build the React Frontend
```
cd frontend
npm install
npm run build
```
🛠 Wait for the application to finish building.

4️⃣ Configure Environment Variables
Edit backend/config/config.env and set your MongoDB connection string:
```
DB_LOCAL_URI=mongodb://localhost:27017/GKCcart
```

5️⃣ Seed Demo Data
Go back to the root folder and run:
```
npm run seeder
```

6️⃣ Run in Production Mode
```
npm run prod
```

🧪 Test Application
Open your browser and navigate to:
```
http://localhost:8000
```
Test frontend routes, API endpoints, and product flows.




