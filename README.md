<div align="center">

# 🎓 Learning Management System (LMS)

### *Developed by Shubham Das*

[![GitHub repo size](https://img.shields.io/github/repo-size/Shubhamdas27/LMS?color=orange&style=for-the-badge)](https://github.com/Shubhamdas27/LMS)
[![GitHub stars](https://img.shields.io/github/stars/Shubhamdas27/LMS?color=yellow&style=for-the-badge)](https://github.com/Shubhamdas27/LMS/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Shubhamdas27/LMS?color=green&style=for-the-badge)](https://github.com/Shubhamdas27/LMS/network)
[![GitHub license](https://img.shields.io/github/license/Shubhamdas27/LMS?color=blue&style=for-the-badge)](https://github.com/Shubhamdas27/LMS/blob/master/LICENSE)

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Full+Stack+LMS+Platform;React+%7C+Node.js+%7C+MongoDB;AI+Powered+Learning+System;Built+by+Shubham+Das" alt="Typing SVG" />

</div>

---

## 📋 Table of Contents

- [✨ Project Overview](#-project-overview)
- [🚀 Features](#-features)
- [🛠️ Technology Stack](#️-technology-stack)
- [📁 Project Structure](#-project-structure)
- [⚡ Quick Start](#-quick-start)
- [🔧 Environment Setup](#-environment-setup)
- [📸 Screenshots](#-screenshots)
- [🎯 Key Features](#-key-features)
- [🔑 API Keys Required](#-api-keys-required)
- [🚀 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👨‍💻 Developer](#-developer)

---

## ✨ Project Overview

**LMS (Learning Management System)** is a comprehensive full-stack web application that revolutionizes online education. Built with modern technologies like React 19, Node.js, and MongoDB, this platform offers a seamless learning experience with AI-powered features, secure payment integration, and real-time analytics.

### 🌟 Why This Project?

This project showcases advanced full-stack development skills including:
- **Modern Frontend Development** with React 19 and Tailwind CSS
- **Robust Backend Architecture** with Node.js and Express
- **AI Integration** using Google Gemini API
- **Payment Processing** with Razorpay
- **Cloud Storage** with Cloudinary
- **Real-time Features** and responsive design

---

## 🚀 Features

<table>
<tr>
<td>

### 🔐 **Authentication & Security**
- JWT-based authentication
- Secure password hashing
- Email verification
- Role-based access control
- Password recovery system

</td>
<td>

### 📚 **Course Management**
- Create and edit courses
- Video lecture uploads
- Progress tracking
- Course categorization
- Search and filter options

</td>
</tr>
<tr>
<td>

### 💳 **Payment Integration**
- Razorpay payment gateway
- Secure transaction processing
- Order management
- Payment history
- Refund handling

</td>
<td>

### 🤖 **AI-Powered Features**
- Intelligent course search
- AI-based recommendations
- Smart content analysis
- Automated course suggestions
- Enhanced user experience

</td>
</tr>
<tr>
<td>

### 📊 **Analytics Dashboard**
- Real-time data visualization
- Student progress tracking
- Revenue analytics
- Course performance metrics
- Interactive charts

</td>
<td>

### 📱 **Responsive Design**
- Mobile-first approach
- Cross-platform compatibility
- Tailwind CSS styling
- Modern UI/UX design
- Accessibility features

</td>
</tr>
</table>

---

## 🛠️ Technology Stack

<div align="center">

### Frontend Technologies
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Backend Technologies
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

### Cloud & Services
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)
![Google AI](https://img.shields.io/badge/Google%20AI-4285F4?style=for-the-badge&logo=google&logoColor=white)

</div>

### 📋 Complete Tech Stack

| **Category** | **Technologies** |
|--------------|------------------|
| **Frontend** | React 19, Vite, Tailwind CSS, Redux Toolkit, React Router DOM |
| **Backend** | Node.js, Express.js, MongoDB, Mongoose, JWT |
| **Authentication** | JSON Web Tokens, Bcrypt, Email Verification |
| **Payment** | Razorpay Payment Gateway |
| **AI Integration** | Google Gemini API |
| **File Storage** | Cloudinary Cloud Storage |
| **Charts** | Recharts for Data Visualization |
| **Email** | Nodemailer for Email Services |
| **Styling** | Tailwind CSS, React Icons |

---

## 📁 Project Structure

```
📦 LMS
├── 📂 backend/
│   ├── 📂 configs/
│   │   ├── 🔧 cloudinary.js
│   │   ├── 🔧 db.js
│   │   ├── 🔧 Mail.js
│   │   └── 🔧 token.js
│   ├── 📂 controllers/
│   │   ├── 🎯 aiController.js
│   │   ├── 🔐 authController.js
│   │   ├── 📚 courseController.js
│   │   ├── 💳 orderController.js
│   │   ├── ⭐ reviewController.js
│   │   └── 👤 userController.js
│   ├── 📂 middlewares/
│   │   ├── 🔐 isAuth.js
│   │   └── 📤 multer.js
│   ├── 📂 models/
│   │   ├── 📚 courseModel.js
│   │   ├── 🎥 lectureModel.js
│   │   ├── 💳 orderModel.js
│   │   ├── ⭐ reviewModel.js
│   │   └── 👤 userModel.js
│   ├── 📂 routes/
│   │   ├── 🤖 aiRoute.js
│   │   ├── 🔐 authRoute.js
│   │   ├── 📚 courseRoute.js
│   │   ├── 💳 paymentRoute.js
│   │   ├── ⭐ reviewRoute.js
│   │   └── 👤 userRoute.js
│   ├── 📄 index.js
│   └── 📄 package.json
├── 📂 frontend/
│   ├── 📂 src/
│   │   ├── 📂 components/
│   │   ├── 📂 pages/
│   │   ├── 📂 redux/
│   │   ├── 📂 customHooks/
│   │   ├── 📂 assets/
│   │   └── 📂 utils/
│   ├── 📄 index.html
│   ├── 📄 package.json
│   └── 📄 vite.config.js
└── 📄 README.md
```

---

## ⚡ Quick Start

### 🔄 Clone the Repository

```bash
git clone https://github.com/Shubhamdas27/LMS.git
cd LMS
```

### 🔧 Backend Setup

```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file with required variables
cp .env.example .env

# Start development server
npm run dev
```

### 🎨 Frontend Setup

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Create .env file with required variables
cp .env.example .env

# Start development server
npm run dev
```

### 🚀 Access the Application

- **Frontend**: http://localhost:5173
- **Backend**: http://localhost:8000

---

## 🔧 Environment Setup

### 📋 Backend Environment Variables (.env)

```bash
# Server Configuration
PORT=8000

# Database
MONGODB_URL="your_mongodb_connection_string"

# Authentication
JWT_SECRET="your_jwt_secret_key"

# Cloudinary Configuration
CLOUDINARY_CLOUD_NAME="your_cloudinary_cloud_name"
CLOUDINARY_API_KEY="your_cloudinary_api_key"
CLOUDINARY_API_SECRET="your_cloudinary_api_secret"

# Email Configuration
EMAIL="your_email@gmail.com"
EMAIL_PASS="your_email_app_password"

# Payment Gateway
RAZORPAY_KEY_ID="your_razorpay_key_id"
RAZORPAY_SECRET="your_razorpay_secret"

# AI Integration
GEMINI_API_KEY="your_gemini_api_key"
```

### 📋 Frontend Environment Variables (.env)

```bash
# Firebase Configuration
VITE_FIREBASE_APIKEY="your_firebase_api_key"

# Payment Gateway
VITE_RAZORPAY_KEY_ID="your_razorpay_key_id"
```

---

## 📸 Screenshots

<div align="center">

### 🏠 Home Page
*Beautiful landing page with modern design and course showcase*

### 📚 Course Dashboard
*Comprehensive course management with analytics*

### 🎓 Learning Interface
*Interactive learning environment with video player*

### 💳 Payment Integration
*Secure payment processing with Razorpay*

### 📊 Analytics Dashboard
*Real-time data visualization and progress tracking*

</div>

> **Note**: Add actual screenshots of your application here once deployed

---

## 🎯 Key Features

### 🔐 **Authentication System**
- **Secure Registration/Login** with email verification
- **JWT-based Authentication** for secure sessions
- **Role-based Access Control** (Student, Educator, Admin)
- **Password Recovery** with email notifications

### 📚 **Course Management**
- **Create & Edit Courses** with rich content editor
- **Video Upload & Streaming** via Cloudinary
- **Progress Tracking** for students
- **Course Categories** and search functionality

### 🤖 **AI Integration**
- **Smart Course Search** using Google Gemini API
- **Personalized Recommendations** based on user behavior
- **Content Analysis** for better course organization
- **Intelligent Q&A** system for student support

### 💳 **Payment Processing**
- **Razorpay Integration** for secure payments
- **Multiple Payment Methods** (Cards, UPI, Wallets)
- **Order Management** and transaction history
- **Automatic Enrollment** after successful payment

### 📊 **Analytics & Reporting**
- **Real-time Dashboard** with interactive charts
- **Student Progress Tracking** and performance metrics
- **Revenue Analytics** for educators
- **Course Performance** insights

---

## 🔑 API Keys Required

<details>
<summary><b>🔍 Click to view detailed API setup instructions</b></summary>

### 1. 🍃 **MongoDB Atlas**
- Visit: [MongoDB Atlas](https://mongodb.com/atlas)
- Create free cluster
- Get connection string
- Add to `MONGODB_URL`

### 2. ☁️ **Cloudinary**
- Visit: [Cloudinary](https://cloudinary.com)
- Create free account
- Get: Cloud Name, API Key, API Secret
- Add to respective environment variables

### 3. 📧 **Gmail App Password**
- Enable 2-Step Verification in Gmail
- Generate App Password
- Add email and app password to environment

### 4. 💳 **Razorpay**
- Visit: [Razorpay](https://razorpay.com)
- Create business account
- Get Key ID and Secret
- Add to environment variables

### 5. 🤖 **Google Gemini AI**
- Visit: [Google AI Studio](https://makersuite.google.com/app/apikey)
- Generate API key
- Add to `GEMINI_API_KEY`

### 6. 🔥 **Firebase**
- Visit: [Firebase Console](https://console.firebase.google.com)
- Create project
- Get API key from project settings
- Add to `VITE_FIREBASE_APIKEY`

</details>

---

## 🚀 Deployment

### 🌐 **Frontend Deployment (Vercel)**

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd frontend
vercel --prod
```

### 🔧 **Backend Deployment (Railway/Render)**

```bash
# For Railway
railway login
railway init
railway up

# For Render
# Connect GitHub repo to Render dashboard
```

### 🗄️ **Database Deployment**
- Use **MongoDB Atlas** for cloud database
- Update connection string in environment variables

---

## 🤝 Contributing

<div align="center">

**Contributions are always welcome!** 🎉

</div>

### 📝 How to Contribute

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### 🐛 Found a Bug?

- **Open an issue** with detailed description
- **Include steps** to reproduce the bug
- **Add screenshots** if applicable

### 💡 Want to Request a Feature?

- **Open an issue** with the feature request
- **Describe the feature** in detail
- **Explain why** it would be useful

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Shubham Das

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 👨‍💻 Developer

<div align="center">

### 🙋‍♂️ **Shubham Das**

*Full Stack Developer | MERN Stack Enthusiast | AI Integration Specialist*

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://your-portfolio-link.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubham-das)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shubhamdas27)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:subhdas272004@gmail.com)

### 📊 **GitHub Stats**

![Shubham's GitHub stats](https://github-readme-stats.vercel.app/api?username=Shubhamdas27&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shubhamdas27&layout=compact&theme=radical)

</div>

---

## 🌟 **Show Your Support**

<div align="center">

**If you found this project helpful, please give it a ⭐!**

[![Star History Chart](https://api.star-history.com/svg?repos=Shubhamdas27/LMS&type=Date)](https://star-history.com/#Shubhamdas27/LMS&Date)

### 💖 **Thank you for visiting!**

*Built with ❤️ by [Shubham Das](https://github.com/Shubhamdas27)*

</div>

---

<div align="center">

**🚀 Ready to revolutionize online learning? Let's build the future together! 🚀**

</div>
