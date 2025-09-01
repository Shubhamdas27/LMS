# Learning Management System (LMS)

**Developer: Shubham Das**

A comprehensive Learning Management System built with modern web technologies. This project demonstrates full-stack development skills with React, Node.js, and advanced features like AI integration, payment processing, and real-time learning analytics.

## 🚀 Features

- **User Authentication & Authorization** - JWT-based secure login/signup
- **Course Management** - Create, edit, and manage courses with video lectures
- **Payment Integration** - Razorpay payment gateway for course purchases
- **AI-Powered Search** - Gemini AI integration for intelligent course recommendations
- **Real-time Analytics** - Dashboard with charts and progress tracking
- **File Upload** - Cloudinary integration for media management
- **Email Services** - Nodemailer for password recovery and notifications
- **Responsive Design** - Mobile-first approach with Tailwind CSS
- **State Management** - Redux Toolkit for efficient state handling

## 🛠️ Technology Stack

### Frontend

- **React 19** - Latest React with modern hooks
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **Redux Toolkit** - State management
- **React Router DOM** - Client-side routing
- **Recharts** - Data visualization
- **Firebase** - Additional services integration

### Backend

- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database with Mongoose ODM
- **JWT** - JSON Web Tokens for authentication
- **Bcrypt** - Password hashing
- **Multer** - File upload handling
- **Cloudinary** - Cloud-based media management
- **Razorpay** - Payment processing
- **Gemini AI** - AI integration for enhanced features
- **Nodemailer** - Email service

## 📦 Installation & Setup

### Prerequisites

- Node.js (v16 or higher)
- MongoDB database
- Required API keys (see Environment Variables section)

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## 🔑 Environment Variables

### Backend (.env)

```env
PORT = 8000
MONGODB_URL = "your_mongodb_connection_string"
JWT_SECRET = "your_jwt_secret_key"
CLOUDINARY_CLOUD_NAME = "your_cloudinary_cloud_name"
CLOUDINARY_API_KEY = "your_cloudinary_api_key"
CLOUDINARY_API_SECRET = "your_cloudinary_api_secret"
EMAIL = "your_email_for_notifications"
EMAIL_PASS = "your_email_app_password"
RAZORPAY_KEY_ID = "your_razorpay_key_id"
RAZORPAY_SECRET = "your_razorpay_secret"
GEMINI_API_KEY = "your_gemini_api_key"
```

### Frontend (.env)

```env
VITE_FIREBASE_APIKEY = "your_firebase_api_key"
VITE_RAZORPAY_KEY_ID = "your_razorpay_key_id"
```

## 🏗️ Project Structure

```
LMS/
├── backend/
│   ├── configs/          # Database, Cloudinary, Mail configurations
│   ├── controllers/      # Route handlers
│   ├── middlewares/      # Authentication, file upload middlewares
│   ├── models/          # MongoDB schemas
│   ├── routes/          # API routes
│   └── index.js         # Server entry point
└── frontend/
    ├── src/
    │   ├── components/   # Reusable React components
    │   ├── pages/       # Page components
    │   ├── redux/       # State management
    │   ├── customHooks/ # Custom React hooks
    │   └── utils/       # Utility functions
    └── public/          # Static assets
```

## 🎯 Key Features Implemented

1. **Authentication System** - Complete user registration, login, and JWT-based authentication
2. **Course Management** - CRUD operations for courses with video lectures
3. **Payment Integration** - Secure payment processing with Razorpay
4. **AI Integration** - Gemini AI for intelligent course search and recommendations
5. **Admin Dashboard** - Analytics and course management for educators
6. **Responsive Design** - Mobile-optimized UI with Tailwind CSS
7. **File Management** - Cloudinary integration for video and image uploads
8. **Email Services** - Automated email notifications and password recovery

## 🚀 Deployment Ready

This project is configured for easy deployment with:

- Environment-based configuration
- Production-ready build scripts
- Modular architecture
- Secure authentication
- Optimized performance

## 📱 Screenshots & Demo

[Add your screenshots and demo links here]

## 🤝 Contributing

This is a portfolio project developed by **Shubham Das**. Feel free to explore the code and suggest improvements!

## 📄 License

This project is developed by **Shubham Das** as a demonstration of full-stack development capabilities.

---

**Developed with ❤️ by Shubham Das**
