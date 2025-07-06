# MERN_SEC - Backend API

This is the backend API for the **MERN_SEC** project, built with **Node.js**, **Express**, **MongoDB**, and **Mongoose**. It includes secure user authentication, cookie-based session handling, and OTP-based email verification (in progress).

---

## 📦 Features

- User registration with hashed password
- Login and logout functionality
- JWT-based authentication
- Cookie handling using `cookie-parser`
- Environment configuration via `.env`
- MongoDB integration via Mongoose
- Modular folder structure for scalability

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB** (via Mongoose)
- **dotenv**
- **bcryptjs**
- **cookie-parser**
- **cors**

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MdTashinParwez/MERN_SEC.git
cd MERN_SEC/BACKEND
```
## 2. Install dependencies
   ```bash
   npm install
   ```
##3. Setup environment variables

```bash
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
## 4. Start the server
```bash
npm run server
```
###📁 Folder Structure
```bash
BACKEND/
│
├── config/           # Database connection
├── controllers/      # Route controller logic
├── models/           # Mongoose schemas
├── routes/           # Express route files
├── .env              # Environment variables
├── .gitignore        
├── package.json
└── server.js         # Entry point
```
###📬 API Endpoints
#Method	Endpoint	Description
#POST	/api/auth/register	Register a new user
#POST	/api/auth/login	Login user
#POST	/api/auth/logout	Logout user


   ## 🤝Contributing
Contributions are welcome! Here's how you can help:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## 📞Contact
For any inquiries or support, feel free to reach out:

📧Email: tashinparwez537@gmail.com <br>
💻 GitHub: [MdTashinParwez](https://github.com/MdTashinParwez)


   
