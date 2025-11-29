# 🌾 Farmify  
A complete MERN stack platform connecting **local farmers** with **consumers**, enabling farmers to list their products and customers to browse, order, and communicate easily.

---

## 🌐 Live Demo

- **Frontend:** https://farmify-frontend-indol.vercel.app/  
- **Backend API:** https://farmify-yjg7.onrender.com/api/

---

# 🚀 Features

## 👨‍🌾 For Farmers
- Secure register/login
- Add products with images, price, and category
- Edit & delete product listings
- View customer orders

## 🛒 For Customers
- Browse all farmer products
- Product search & filtering
- View detailed product pages
- Place orders
- Send messages to farmers

## 🔐 Authentication
- JWT-based secure login
- Encrypted passwords (bcrypt)
- Protected routes

## 🧩 Backend Features
- CRUD operations for:
  - Users
  - Products
  - Orders
  - Categories
  - Messages
- MongoDB (Mongoose)
- Render Deployment

## 💻 Frontend Features
- Built using React + Vite
- Context API global state
- Fully responsive UI
- Axios API integration
- Clean routing and dashboards

---

# 🏗 Tech Stack

### **Frontend**
- React.js  
- Vite  
- Axios  
- React Router  
- Context API
- Vercel

### **Backend**
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JSON Web Token (JWT)  
- Bcrypt  
- Render  

---

# 📁 Project Structure

## Backend Folder Structure
```markdown
farmify-backend/
│── controllers/
│── routes/
│── models/
│── middleware/
│── db/
│── index.js
│── .env
│── package.json
```

## Frontend Folder Structure
```markdown
farmify-frontend/
│── src/
│ ├── components/
│ ├── pages/
│ ├── context/
│ ├── api/
│── vite.config.js
│── .env
│── package.json
```

---

# 🔧 Installation & Setup Guide

## 1️⃣ Clone Repositories

git clone https://github.com/YasojiAbhilash/farmify-backend

git clone https://github.com/YasojiAbhilash/farmify-frontend


---

# 🗄 Backend Setup (Node + Express)

### Install dependencies:
cd farmify-backend
npm install


### Create `.env` file:
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key


### Start Backend Server:

Backend will run on:
http://localhost:5000

---

# 🎨 Frontend Setup (React + Vite)

### Install dependencies:
cd farmify-frontend
npm install

### Create `.env`:
VITE_API_URL=http://localhost:5000/api

### Start Frontend:
npm run dev


Frontend will run on:
http://localhost:5173


---

# 📡 API Endpoints

## 🔐 Auth Routes
- POST /api/auth/register
- POST /api/auth/login
- GET /api/auth/me

## 👤 Users
- GET /api/users
- GET /api/users/:id
- DELETE /api/users/:id



## 🛒 Products
- GET /api/products
- GET /api/products/:id
- POST /api/products
- PUT /api/products/:id
- DELETE /api/products/:id

## 🗂 Categories
- GET /api/categories
- POST /api/categories
- DELETE /api/categories/:id

## 📦 Orders
- GET /api/orders
- POST /api/orders

## 💬 Messages
- POST /api/messages

---

# 🚀 Deployment Information

## Frontend  
Deployed on **Vercel**  
Uses `VITE_API_URL` for API connection.

## Backend  
Deployed on **Render**  
Auto-deploys from GitHub.

---

# 🧪 Testing with Postman

### Local:
http://localhost:5000/api

### Production:
https://farmify-yjg7.onrender.com/api

You can test:
- Login/Register  
- Add products  
- Delete users/products  
- View categories  
- Place order  

---
 
---

# 🤝 Contribution

Contributions, pull requests, and feature suggestions are welcome!

---

# 🧑‍💻 Author

## Team Members

| Name | Role | GitHub | Linkedin |
|------|------|--------|--------|
| Abhilash Yasoji | Backend Developer | [@Abhilash](https://github.com/YasojiAbhilash) | [@Abhilash](https://www.linkedin.com/in/abhilash-yasoji/)
| Bhuvaneshwar Mushke | Q/A Tester  | [@Bhuvan](https://github.com/member2) | [@Bhuvan](https://www.linkedin.com/in/bhuvaneshwar-mushke/)
| Sathish Kuthala | Frontend Developer | [@Sathish](https://github.com/member3) | [@Sathish](https://www.linkedin.com/in/sathishkuthala/)
| Teja Kolupula | Frontend Developer | [@Teja](https://github.com/member4) | [@Teja](https://www.linkedin.com/in/kolupula-teja-3192612b4/)


---

# ⭐ Support
If you like this project, please ⭐ **star the repository** on GitHub!

---

