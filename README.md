# FastAPI + React Pipeline Builder Project

## 📌 Project Description

This project is a **full-stack web application** built using **FastAPI (Backend)** and **React (Frontend)**.
It allows users to create and visualize pipelines by connecting nodes, similar to a flow-based editor.

The backend handles API requests, data validation, and pipeline logic, while the frontend provides an interactive drag-and-drop UI.

---

## 🛠 Tech Stack

### Backend

* Python 3.13
* FastAPI
* Pydantic
* Uvicorn

### Frontend

* React.js
* JavaScript (ES6)
* HTML5
* CSS3

### Tools

* Git & GitHub
* VS Code
* Node.js & npm

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Devel95/fastapi-react-project.git
cd fastapi-react-project
```

---

### 2️⃣ Run Backend (FastAPI)

```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend will run at:

```
http://127.0.0.1:8000
```

API Docs:

```
http://127.0.0.1:8000/docs
```

---

### 3️⃣ Run Frontend (React)

```bash
cd frontend
npm install
npm start
```

Frontend will run at:

```
http://localhost:3000
```

---

## 🖼 Screenshots

> Add screenshots of the application UI here.

Example:

```md
![Pipeline UI](screenshots/pipeline-ui.png)
![API Docs](screenshots/api-docs.png)
```

📂 **Recommended Folder Structure**

```
screenshots/
 ├── pipeline-ui.png
 ├── api-docs.png
```

---

## ✅ Features

* Interactive pipeline builder
* Node and edge management
* FastAPI backend with validation
* React-based frontend UI
* CORS enabled for frontend-backend communication

---

## 📄 License

This project is for educational and learning purposes.
---

## 📸 Screenshots

### Frontend UI
![Frontend UI](screenshots/frontend.png)

### Backend API (Swagger Docs)
![Backend API](screenshots/backend.png)
