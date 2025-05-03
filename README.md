# 🏥 Pallava - Clinic Management System

A full-stack Clinic Mangement System that allows patients to book appointments with doctors online. The application includes an **Admin Panel**, **Doctor Management**, and **Patient Appointment System**. Built using the **MERN stack (MongoDB, Express, React, Node.js)**, styled with **Tailwind CSS**, and supports **image uploading via Cloudinary**.

---

## 🚀 Features

### 🔒 Admin Module
- Admin authentication (login/logout)
- Manage doctor profiles (Add, Update, Delete)
- View and manage all user appointments
- Approve or reject doctor registrations
- Dashboard with analytics

### 👨‍⚕️ Doctor Module
- Doctor registration and login
- Manage available time slots
- View patient appointments
- Profile management with image upload (Cloudinary)

### 👤 Patient Module
- Patient registration and login
- Book appointments with doctors
- View and cancel appointments
- Profile update with image upload (Cloudinary)

---

## 🛠 Tech Stack

### Frontend
- **React.js**
- **Tailwind CSS**
- **Axios** (for API requests)
- **React Router DOM**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB + Mongoose**
- **Cloudinary** (image uploads)
- **JWT** (authentication)
- **Multer** (file uploads)
- **Bcrypt** (password hashing)

## 📸 Image Uploading with Cloudinary

- Uses **Multer** middleware to handle file uploads.
- Images are uploaded to **Cloudinary**, and the secure URL is stored in the database.
- Used for **user** and **doctor** profile pictures.

---

## ✅ Future Enhancements

- 📧 Email/SMS notifications  
- 💳 Payment integration for appointment fees  
- 💬 Real-time chat between doctor and patient  
- 🔍 Pagination and search filters  

---

## 🙌 Acknowledgements

- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/)
- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Cloudinary](https://cloudinary.com/)
