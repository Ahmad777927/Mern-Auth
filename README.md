# 🔐 MERN Advanced Authentication System

A full-stack authentication system built with the **MERN Stack** (MongoDB, Express.js, React, Node.js) featuring secure authentication, email verification, password reset, JWT authentication, and modern frontend architecture.

---

## 🚀 Features

### Authentication
- ✅ User Registration
- ✅ User Login
- ✅ Secure Logout
- ✅ JWT Authentication
- ✅ Access Token & HTTP-only Cookies
- ✅ Protected Routes
- ✅ Authentication Middleware
- ✅ Persistent Authentication
- ✅ Session Management

### Email Verification
- 📧 Email Verification after Registration
- 📩 Verification Email using Express Mailer
- 🔑 Verification Token Generation
- ⏳ Token Expiration Handling
- ✅ Account Activation

### Password Management
- 🔒 Forgot Password
- 🔄 Reset Password
- 🔑 Secure Reset Tokens
- ⌛ Token Expiration
- 🔐 Password Hashing with bcrypt

### Security
- Password Hashing (bcrypt)
- JWT Authentication
- Environment Variables
- Secure API Routes
- Input Validation
- Error Handling
- Protected Backend Routes
- Authentication Middleware
- Cookie Parser
- CORS Configuration

### Frontend
- React 19
- React Router DOM
- Axios
- Context API / State Management
- Protected Routes
- Responsive UI
- Toast Notifications
- Loading States
- Form Validation

---

# 🛠 Tech Stack

## Frontend

- React
- React Router DOM
- Axios
- Tailwind CSS
- React Hot Toast

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- Nodemailer
- Cookie Parser
- dotenv
- CORS

---

# 📂 Project Structure

```
mern-auth/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── mail/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── routes/
│   │   └── App.jsx
│   │
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/mern-auth.git

cd mern-auth
```

---

## Backend Setup

```bash
cd backend

npm install
```

Create a `.env` file

```env
PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:5173

NODE_ENV=development

EMAIL_USER=your_email@gmail.com

EMAIL_PASS=your_email_password

SMTP_HOST=smtp.gmail.com

SMTP_PORT=587
```

Start Backend

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd frontend

npm install
```

Create `.env`

```env
VITE_API_URL=http://localhost:5000/api
```

Run Frontend

```bash
npm run dev
```

---

# 📬 Authentication Flow

```
User Register
      │
      ▼
Create Account
      │
      ▼
Send Verification Email
      │
      ▼
Verify Email
      │
      ▼
Login
      │
      ▼
Generate JWT Token
      │
      ▼
Protected Routes
      │
      ▼
Authenticated User
```

---

# 🔒 Security Features

- JWT Authentication
- bcrypt Password Hashing
- HTTP-only Cookies
- Secure Authentication Middleware
- Email Verification
- Password Reset Tokens
- Token Expiration
- Protected Routes
- Environment Variables
- CORS Configuration
- Input Validation
- Error Handling

---

# 💻 Available Scripts

### Backend

```bash
npm run dev
npm start
```

### Frontend

```bash
npm run dev
npm run build
npm run preview
```

---

# 📸 Screens

- Login Page
- Register Page
- Email Verification Page
- Forgot Password
- Reset Password
- Dashboard

---

# 🌟 Future Improvements

- Google Authentication
- GitHub Authentication
- Two-Factor Authentication (2FA)
- Refresh Token Rotation
- User Profile
- Change Password
- Email Change Verification
- Account Lock After Multiple Failed Attempts
- Rate Limiting
- Role-Based Access Control (RBAC)

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add Amazing Feature"
```

4. Push

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Ahmad Arshad**

Frontend Developer | MERN Stack Developer

- React.js
- Node.js
- Express.js
- MongoDB
- JavaScript
- Tailwind CSS

⭐ If you found this project useful, don't forget to star the repository!
