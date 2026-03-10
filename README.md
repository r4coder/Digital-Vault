# 🔐 VaultX – Secure Digital Document Vault

![VaultX Banner](https://via.placeholder.com/1200x400/123458/F1EFEC?text=VaultX+Secure+Digital+Vault)

VaultX is a **secure cloud-based digital document vault** built using the **MERN Stack (MongoDB, Express, React, Node.js)**.
It allows users to **upload, store, organize, and manage sensitive files securely** with authentication, encrypted storage, and activity monitoring.

The application provides a **modern dashboard interface**, role-based access, and secure file management capabilities suitable for personal document storage.

---

# 🚀 Features

## 🔐 Secure Authentication

* JWT-based authentication system
* Password hashing using **bcrypt**
* Secure login and signup workflow
* Password change functionality
* Protected API routes

## 📁 File & Folder Management

* Upload and store files securely
* Folder-based document organization
* Drag & Drop file upload support
* Move, delete, and preview files
* Real-time storage usage tracking

## 🔍 Smart Search

* Global search across files and folders
* Fast metadata-based search queries
* Instant results using indexed MongoDB queries

## 📊 Activity Audit Trail

* Tracks all user actions:

  * Login
  * File Upload
  * File Delete
  * Folder Creation
* Maintains a **security audit log** for monitoring activity

## 👤 User Profile & Dashboard

* Dynamic user profile
* Storage usage statistics
* File count overview
* Account tier display (Free / Pro)

## 🎨 Modern UI

* Fully responsive interface
* Built with **Tailwind CSS**
* Professional **Dark Navy + Beige theme**
* Clean file browser UI
* Toast notifications for user feedback

---

# 🛠 Tech Stack

## Frontend

* React.js (Vite)
* Tailwind CSS
* React Router
* Lucide React Icons

## Backend

* Node.js
* Express.js
* MongoDB with Mongoose
* JWT Authentication
* Multer File Upload Middleware

## Cloud Services

* Cloudinary (File storage and hosting)

---

# 🏗 Project Architecture

```
VaultX
│
├── client (React Frontend)
│   ├── components
│   ├── pages
│   ├── services
│   └── styles
│
├── server (Node + Express Backend)
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── config
│
└── database
    └── MongoDB
```

---

# 📸 Application Screenshots

### Dashboard

![Dashboard](https://via.placeholder.com/600x300/123458/ffffff?text=File+Browser+View)

### Profile & Settings

![Profile](https://via.placeholder.com/600x300/123458/ffffff?text=User+Profile+Page)

### Activity Audit Trail

![Audit](https://via.placeholder.com/600x300/123458/ffffff?text=Activity+Log+Timeline)

### Global Search

![Search](https://via.placeholder.com/600x300/123458/ffffff?text=Secure+Search)

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```
git clone https://github.com/r4coder/Digital-Vault.git
cd Digital-Vault
```

---

## 2️⃣ Install Backend Dependencies

```
cd server
npm install
```

---

## 3️⃣ Install Frontend Dependencies

```
cd ../client
npm install
```

---

## 4️⃣ Environment Variables

Create a `.env` file in the **server folder**:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## 5️⃣ Run the Application

Start backend:

```
cd server
npm run dev
```

Start frontend:

```
cd client
npm run dev
```

Application will run on:

```
Frontend → http://localhost:5173
Backend → http://localhost:5000
```

---

# 📡 API Overview

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| POST   | /api/auth/register | Register new user |
| POST   | /api/auth/login    | User login        |
| POST   | /api/files/upload  | Upload file       |
| GET    | /api/files         | Get user files    |
| DELETE | /api/files/:id     | Delete file       |
| GET    | /api/search        | Search files      |

---

# 🔒 Security Features

* JWT authentication
* Password hashing using bcrypt
* Protected backend routes
* File metadata validation
* Activity audit logging
* Secure cloud storage

---

# 🚀 Future Improvements

* End-to-end encryption
* Two-factor authentication (2FA)
* File sharing with secure links
* File version history
* Mobile app integration
* Storage analytics dashboard

---

# 👨‍💻 Author

**Ritheesh Reddy**

GitHub
https://github.com/r4coder

---

# ⭐ Support

If you like this project, please ⭐ the repository to support development.
