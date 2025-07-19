# 🏥 Medicare Pro – Full-Stack Hospital Management System

**Medicare Pro** is a robust, role-based hospital management platform built with the MERN stack. It provides secure login for Admins, Doctors, and Patients, appointment scheduling, billing, prescription tracking, and real-time analytics. The system is designed to streamline healthcare operations with modern web technology and seamless UI/UX.

---

## 🖼️ Project Preview

![Preview](./frontend/public/image.png) <!-- Replace with actual preview image -->

---

## 🚀 Features

* 🧑‍⚕️ Role-based Dashboards (Admin / Doctor / Patient)
* 📅 Appointment Booking and Calendar View
* 📝 Prescription Upload and Download
* 📊 Patient Analytics and Medical History
* 💳 Razorpay and Stripe Integration for Billing
* ☁️ Cloudinary Integration for Image Uploads
* ✉️ Email Notifications (e.g., appointment confirmation)
* 🔐 JWT-based Authentication and Route Protection
* 📁 Responsive UI built with React + Tailwind

---

## 🔧 Tech Stack

### Frontend

* React.js (with Vite)
* Tailwind CSS
* Axios

### Backend

* Node.js + Express.js
* MongoDB Atlas
* JWT Auth
* Cloudinary
* Razorpay & Stripe APIs
* Nodemailer

---

## 📁 Folder Structure

```
MedicarePro/
├── backend/
├── frontend/
├── admin/
├── README.md
└── .env.example
```

---

## ⚙️ Installation & Setup

### Step 1: Clone the Project

```bash
git clone https://github.com/<your-username>/MedicarePro.git
cd MedicarePro
```

---

### Step 2: Backend Setup

```bash
cd backend
npm install
npm install bcryptjs
```

#### Add `.env` File

Create a `.env` file in `backend/` using the template below:

```env
CURRENCY=INR
JWT_SECRET=greatstack
ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=greatstack123
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/MedicarePro
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```

#### Start Backend Server

```bash
npm run server
```

Visit: `http://localhost:4000`

---

### Step 3: Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

Visit: `http://localhost:5173`

---

### Step 4: Admin Panel Setup

```bash
cd ../admin
npm install
npm run dev
```

Visit: `http://localhost:5174`

---

## 👨‍⚕️ Admin Credentials (Demo)

```env
Email: admin@example.com
Password: greatstack123
```

---


## 🔗 Author

* **Ravi M Shetty**
  [GitHub](https://github.com/Ravishetty07) | [Portfolio](https://ravishetty-portfolio.netlify.app) | [LinkedIn](https://linkedin.com/in/ravi-m-shetty/)

---

Let’s build smarter hospitals together with **Medicare Pro** 🚀
