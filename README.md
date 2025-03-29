# 🚀 Backend CRUD API (NestJS + MySQL)

This is the **backend API** for a **CRUD (Create, Read, Update, Delete) application** built with **NestJS** and **MySQL**. It provides RESTful endpoints for managing resources.

## 🌟 Features
✅ RESTful API with NestJS  
✅ CRUD operations (Create, Read, Update, Delete)  
✅ MySQL database integration  
✅ Data validation with `class-validator`  
✅ Environment variable support (`.env`)  
✅ Clean and modular architecture  

---

## 🛠️ Tech Stack
- **NestJS** - Progressive Node.js framework  
- **MySQL** - Relational database  
- **TypeORM** - ORM for database management  
- **Swagger** - API documentation  
- **Docker** (optional) - Containerization  

---

## 📦 Installation & Setup

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/repo-name.git
cd backend
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Set Up Environment Variables**
Create a **`.env`** file and add:
```ini
DB_HOST=localhost
DB_PORT=3306
DB_USERNAME=root
DB_PASSWORD=yourpassword
DB_NAME=crud_mysql_dev
PORT=5000
JWT_SECRET=your-secret-key
```
(Replace with your actual database credentials)

### **4️⃣ Run Database Migrations (if using TypeORM)**
```sh
npm run migration:run
```

### **5️⃣ Start the Development Server**
```sh
npm run start:dev
```
🚀 Your API will be live at **`http://localhost:5000`**

---

## 📌 Folder Structure
```
📦 backend
 ┣ 📂 src
 ┃ ┣ 📂 modules    # Feature modules (e.g., users, auth)
 ┃ ┣ 📂 config     # Configuration files
 ┃ ┣ 📂 database   # Database connection
 ┃ ┣ 📂 middlewares # Custom middlewares
 ┃ ┣ 📜 main.ts    # Entry point
 ┣ 📜 .env         # Environment variables
 ┣ 📜 package.json
 ┣ 📜 README.md
```

---

## ⚡ API Endpoints
| Action  | Method | Endpoint |
|---------|--------|----------------|
| Get All Users | GET | `/api/users` |
| Get User by ID | GET | `/api/users/:id` |
| Create User | POST | `/api/users` |
| Update User | PUT | `/api/users/:id` |
| Delete User | DELETE | `/api/users/:id` |

---

## 🐳 Docker (Optional)
### **Run Backend in Docker**
```sh
docker-compose up --build
```

---

## 🚀 Deployment
### **To Deploy on Render**
1️⃣ **Push code to GitHub**  
2️⃣ **Go to [Render](https://render.com/)**  
3️⃣ **Create a new Web Service**  
4️⃣ **Set up environment variables**  
5️⃣ **Deploy 🚀**  

---

## 🤝 Contributing
1. Fork the repo  
2. Create a new branch: `git checkout -b feature-branch`  
3. Commit changes: `git commit -m "Added new feature"`  
4. Push: `git push origin feature-branch`  
5. Open a Pull Request  

---

## 📜 License
This project is **MIT licensed**.  

