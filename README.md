Valiant — Clothing store platform

A full-stack application built with a production mindset, focusing on scalability, performance, and real-world workflows such as authentication, payments, caching, and admin operations.

This project is not a toy CRUD app — it simulates how a real online store works end-to-end.

🚀 Why Valiant?

Most student projects stop at “add to cart.”
Valiant goes further by implementing:

Secure authentication & authorization

Admin-level controls

Payment gateway integration

Performance optimization using Redis

Clean backend architecture suitable for scaling

🧩 Core Features
👤 User Side

User authentication using JWT

Product browsing with text-based search

Add to cart, wishlist, and order tracking

Secure checkout using Stripe & Razorpay

Order history and status updates

🛠 Admin Side

Admin authentication & protected routes

Manage products, users, and orders

Update order statuses

Centralized admin dashboard

⚙️ Tech Stack

Frontend

React

Tailwind CSS

Axios

Backend

Node.js

Express.js

MongoDB (Mongoose)

Redis (caching)

JWT Authentication

Payments

Stripe

Razorpay

Deployment / DevOps

Docker (in progress)

Environment-based configuration

🏗 Architecture Overview

Client (React) communicates with backend APIs

Backend (Node + Express) handles business logic

MongoDB stores persistent data (users, products, orders)

Redis caches frequently accessed data to reduce DB load

Payment gateways handle secure transactions

🧠 Performance Optimization

Redis caching implemented for frequently accessed endpoints

Reduced database calls for admin order listings

Optimized API responses using lean queries

🔐 Security Measures

JWT-based authentication

Role-based access control (User / Admin)

Secure password hashing

Environment variables for sensitive credentials

Input validation to prevent common attacks

🧪 Project Status

✅ Core features implemented

✅ Payments integrated

✅ Redis caching added

⏳ Dockerization (in progress)

⏳ Automated tests (planned)

🛠 Local Setup
1️⃣ Clone the Repository
git clone https://github.com/Harshyadav0987/Valiant-E-Commerce.git
cd Valiant-E-Commerce

2️⃣ Setup Environment Variables

Create .env files for backend and frontend using .env.example.

3️⃣ Install Dependencies
# Backend
cd backend
npm install

# Frontend
cd frontend
npm install

4️⃣ Run the Application
# Backend
npm run server

# Frontend
npm run dev

🌐 Live Demo

🔗 Live URL: https://valiant-0t1s.onrender.com/
📸 Screenshots: 
<img width="1918" height="977" alt="Screenshot 2025-12-13 172734" src="https://github.com/user-attachments/assets/e3bf8935-a5f6-4f25-85a8-6717b16f6f71" />
<img width="1917" height="977" alt="Screenshot 2025-12-13 172755" src="https://github.com/user-attachments/assets/3207eb56-2571-483d-bfbf-d53b4ecfa063" />
<img width="1916" height="979" alt="Screenshot 2025-12-13 172807" src="https://github.com/user-attachments/assets/ee38eb84-6c01-4920-8713-1d06810cb150" />
<img width="1917" height="972" alt="Screenshot 2025-12-13 172824" src="https://github.com/user-attachments/assets/9749c0d8-1ada-41b8-a25f-410b15768f7d" />
<img width="1919" height="867" alt="Screenshot 2025-12-13 172839" src="https://github.com/user-attachments/assets/1ab17957-3251-41f8-b344-d872c00c682c" />

Admin Panel

<img width="1914" height="976" alt="Screenshot 2025-12-13 172907" src="https://github.com/user-attachments/assets/b95c9500-2c7f-4926-8fc9-99e2165e68dc" />
<img width="1919" height="980" alt="Screenshot 2025-12-13 173242" src="https://github.com/user-attachments/assets/edc81021-f569-4088-b710-c7101aaaddc4" />
"https://github.com/user-attachments/assets/c19ddfe3-b56a-44ce-a1e3-e48b07d1b016" />
