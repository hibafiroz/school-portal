# 🎓 School Portal  

A full-stack school management web application built with **Node.js**, **Express.js**, and **EJS**, featuring **JWT authentication**, **role-based access**, **real-time chat using Socket.io**, **file uploads using Multer**, **responsive UI with Tailwind CSS**, and **JSON-based local data storage**.

---

## 🚀 Features  

### Authentication & Roles  
- JWT-based authentication (Register / Login / Logout)  
- Role-based access control (**Admin / Student**)  
- Protected routes using middleware  

### Admin Capabilities  
- Upload bulletins with file attachments (Multer)  
- Add / Edit / Delete students  
- Manage student records  

### Student Capabilities  
- View admin bulletins  
- Participate in group chat  
- Private one-to-one chat  

### Real-Time Communication  
- Group chat using Socket.io  
- Private messaging using Socket.io  

### Core Functionality  
- CRUD operations  
- File uploads using Multer  
- Responsive UI built with Tailwind CSS  
- JSON file storage for data  
- Server-side rendering with EJS  
- MVC architecture  
- Custom middleware & utilities  
- Static assets served from `public/`  

---

## 🛠 Tech Stack  

- Node.js  
- Express.js  
- EJS  
- JSON Web Tokens (JWT)  
- Socket.io  
- Multer  
- Tailwind CSS  
- JavaScript  
- JSON (local storage)

---

## ▶️ Run Locally  

### 1. Clone repository  

```bash
git clone https://github.com/hibafiroz/school-portal.git
```

### 2. Install dependencies  

```bash
npm install
```

### 3. Create `.env` file  

```
PORT=3303
secretKey=your_secret_key_here
```

### 4. Start server  

```bash
npm start
```

### 5. Open in browser  

```
http://localhost:3303
```

---

## Authentication  

Uses **JWT (JSON Web Tokens)** for secure login.  
Tokens are validated through middleware to protect Admin and Student routes.

---

## 📄 License  

Open-source project for learning purposes.
