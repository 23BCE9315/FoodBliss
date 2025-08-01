# 🍽️ FoodBliss — Smart Recipe Finder & Food Ordering Platform

**FoodBliss** is a full-stack web application that helps users discover recipes based on ingredients and order food online. It provides a smooth user experience with a clean frontend and a powerful Node.js + MongoDB backend.

---

## 🚀 Features

- 🔍 **Recipe Finder** – Search recipes by entering available ingredients  
- 🛒 **Order Food** – Place food orders through the platform  
- 👤 **User Auth** – Register/Login with JWT authentication  
- 🧠 **MongoDB Integration** – Stores users, recipes, and orders  
- 🖥️ **Responsive Frontend** – Built using HTML, CSS, and JavaScript  
- 💡 **Modular Backend** – Uses Express.js routing and Mongoose models  

---

## 📁 Project Structure

```
foodbliss/
│
├── .gitignore
├── public/ # Frontend HTML, CSS, JS files
│ ├── about.html
│ ├── admin-dashboard.html
│ ├── admin-login.html
│ ├── contact.html
│ ├── index.html
│ ├── login.html
│ ├── order.html
│ ├── profile.html
│ ├── recipes.html
│ ├── scripts/
│ └── styles/
│
├── backend/ # Backend with Node.js, Express.js
│ ├── config/
│ ├── models/
│ ├── routes/
│ ├── scripts/
│ ├── .env # Environment variables
│ ├── package.json
│ ├── package-lock.json
│ └── server.js
│
└── .vscode/ # VS Code settings
```

---

## 🛠️ Tech Stack

| Layer     | Tech Used                         |
|-----------|-----------------------------------|
| Frontend  | HTML, CSS, JavaScript             |
| Backend   | Node.js, Express.js               |
| Database  | MongoDB Atlas (or local MongoDB)  |
| Tools     | VS Code, GitHub, MongoDB Compass  |

---

## 🛡️ .gitignore Summary

The `.gitignore` file is configured to ignore:

- `node_modules/` – local dependencies  
- `.env` – contains sensitive environment variables  
- `*.log`, `.DS_Store`, `*.pid`, `*.tgz` – temp/log files  
- `.vscode/`, `dist/`, `.next/`, `.parcel-cache/` – IDE/build tool folders

---

## 🔧 How to Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/23BCE9315/FoodBliss.git
cd FoodBliss
```

### 2. Setup the Backend

```bash
cd backend
npm install
```

### 3. Create `.env` File

Create a `.env` file inside the `backend` folder with the following content:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Start the Server

```bash
node server.js
```

Your server will start at `http://localhost:5000`.

### 5. Open Frontend

Open public/index.html in your browser

---

## 💡 Screenshots


<img width="1914" height="960" alt="HomePage" src="https://github.com/user-attachments/assets/93deb305-d5f6-464a-87bf-26d6c8a7bb23" />
<img width="1906" height="968" alt="Admin_Dashboard" src="https://github.com/user-attachments/assets/1d44c643-0730-417a-8458-67e83c9ae7f6" />
<img width="1897" height="963" alt="Screenshot 2025-08-01 221433" src="https://github.com/user-attachments/assets/7951c54a-7b63-45f5-a416-fff210fbc896" />
<img width="1910" height="918" alt="Screenshot 2025-08-01 221528" src="https://github.com/user-attachments/assets/ec857d68-ccf0-4de4-9add-257b10828648" />
<img width="1919" height="918" alt="Screenshot 2025-08-01 221623" src="https://github.com/user-attachments/assets/1bee7208-ef37-47a3-a58a-2b5ef4627167" />


---


## 📜 License

This project is licensed under the **MIT License**.

---

## 🙋‍♀️ Author

- 💼 Developed by Purini Durgamma
- 🌐 GitHub: [23BCE9315](https://github.com/23BCE9315)
