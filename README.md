# FastAPI - Blog

[FastAPI - Blog](https://fastapi-blog-tibe.onrender.com/docs#/)

## 📌 Project Overview
FastAPI - Blog is a backend API project built with **FastAPI**, designed to handle blog management and user authentication.  
This project was developed as part of learning FastAPI and focuses on understanding modern API development, authentication flows, and database interactions.


<img width="1280" height="727" alt="Image" src="https://github.com/user-attachments/assets/2fb4c502-312c-4f56-8b6c-97cd8bb76fde" />

---

## 🚀 Features
- User Registration and Authentication (JWT-based)
- Blog CRUD operations (Create, Read, Update, Delete)
- Secure password handling with hashing
- SQLite database integration with SQLAlchemy ORM
- Token-based login system
- Modular project structure using routers

---

## 🛠️ Technologies Used
- **FastAPI** – Web framework for building APIs
- **Uvicorn** – ASGI server for running FastAPI apps
- **SQLAlchemy** – ORM for database interactions
- **SQLite** – Lightweight relational database
- **Passlib** – Password hashing
- **Python-Jose** – JWT token handling
- **Python-Multipart** – Form data handling

---

## 📂 Project Structure
```
FastAPI-Blog/
│── blog/
│   ├── main.py              # Entry point for FastAPI app
│   ├── models.py            # Database models
│   ├── schemas.py           # Pydantic schemas
│   ├── database.py          # Database connection
│   ├── routers/             # API routes (blog, user, auth)
│── blog.db                  # SQLite database
│── requirements.txt         # Dependencies
│── Procfile                 # Deployment configuration
│── README.md                # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/RNNivash/FastAPI-Blog.git
cd FastAPI-Blog
```

### 2️⃣ Create Virtual Environment
```bash
python -m venv env
source env/bin/activate   # On Linux/Mac
env\Scripts\activate    # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
uvicorn blog.main:app --reload
```

Visit: **http://127.0.0.1:8000/docs** for Swagger UI.

---

## 🌐 Deployment
The app can be deployed on platforms like **Railway** or **Render** using the provided `Procfile`.  
Procfile example:
```
web: uvicorn blog.main:app --host 0.0.0.0 --port $PORT
```

---

## 📸 API Documentation
FastAPI provides **interactive API docs**:
- Swagger UI → `/docs`
- ReDoc → `/redoc`

---

## 📌 Learning Outcomes
- Understood how to structure FastAPI projects with routers.
- Learned JWT-based authentication and secure password storage.
- Hands-on experience with deploying FastAPI apps on cloud platforms.
- Improved knowledge of Python backend development.

---

## 📜 License
This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

## 📬 Connect with Me

- LinkedIn: [Nivash](https://www.linkedin.com/in/nivash-r-n/)
- Portfolio: [Nivash](https://rnnivash.github.io/My_Port/)
- Email: [hello.nivashinsights@gmail.com](mailto:hello.nivashinsights@gmail.com)

🔍 **Let's leverage data science to make healthcare better!** 🚀
