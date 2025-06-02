# Medicine-Sphere Backend — RESTful API for Medicine Management

This is the backend API for Medicine-Sphere, a full-stack healthcare and medicine management platform. It handles user authentication, medicine data, prescriptions, orders, and admin operations with a secure and scalable Node.js + TypeScript architecture.

🌐 **Live Site:** [medicine-sphere.vercel.app](medi-sphere-one.vercel.app/)  
📁 **Frontend Repo:** [`medicine-sphere-client`](https://github.com/ArifMiah07/medicine-sphere-client)
<!--📁 **Backend Repo:** [`medicine-sphere-backend`](https://github.com/ArifMiah07/medicine-sphere-backend)-->

(This project was mainly a group project)

🌐 **Live Site:** [medi-sphere.vercel.app](https://medi-sphere-five.vercel.app/)  
📁 **Frontend Repo:** [`medi-sphere-client`](https://github.com/Faey2023/medi-sphere)
📁 **Backend Repo:** [`medi-sphere-backend`](https://github.com/farrdin/medi-sphere-backend)


## Tech Stack

- **Language:** TypeScript
- **Runtime:** Node.js with Express.js
- **Database:** MongoDB using Mongoose ODM
- **Authentication:** JWT (JSON Web Token)
- **Security:** Helmet, CORS, Rate Limiting, Input Sanitization
- **Image Storage:** Cloudinary for image and prescription uploads
- **Payment Processing:** SSLCommerz Integration
- **Architecture:** MVC (Model-View-Controller) pattern

---

## Core Features

- **User Management:** User registration, login, and role-based access control
- **Authentication:** Secure JWT authentication middleware
- **Medicine Management:** Full CRUD for medicines with advanced filters
- **Order System:** Order creation, history tracking, and payment status
- **Prescription System:** Prescription uploads and verification system (via Cloudinary)
- **Admin Dashboard:** Admin tools for managing medicines, users, and orders
- **Payment Integration:** SSLCommerz integration for payment processing
- **Data Validation:** Error handling and validation with express-validator or Zod

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ArifMiah07/medicine-sphere-backend
cd medicine-sphere-backend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file based on `.env.example`:

```bash
cp .env.example .env
```

Fill in your MongoDB URI, JWT secrets, Cloudinary credentials, and SSLCommerz keys.

### 4. Run the development server

```bash
npm run dev
```

Server runs at `http://localhost:5000` by default.

