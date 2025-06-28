# ✅ Dockerized Flask To-Do App

A simple, responsive To-Do list web application built with **Flask**, **SQLite**, and **Docker**. This app lets users add, update, and delete tasks with real-time timestamps. It's designed for beginners in web development, DevOps, and Docker.

---

## 🚀 Features

- 🧾 Add, edit, delete tasks (CRUD operations)
- 🕒 Timestamp using Indian Standard Time (IST)
- 🗃️ Uses SQLite for lightweight data storage
- 🐳 Fully containerized with Docker
- 🎨 Clean HTML templates using Jinja2

---

## 📦 Tech Stack

- Python 3.10
- Flask
- Flask-SQLAlchemy
- SQLite
- HTML & CSS (Jinja2 Templates)
- Docker

---

## 🐳 Run Locally with Docker

### 1. Clone the repo
```bash
git clone https://github.com/sandeep210204/flask-todo-docker.git
cd flask-todo-docker
```

### 2. Build the Docker image
```bash
docker build -t flask-todo-app .
```

### 3. Run the container
```bash
docker run -p 5000:5000 flask-todo-app
```

### 4. Open in Browser
Go to: [http://localhost:5000](http://localhost:5000)

---

## 📁 Project Structure

```
flask-todo-docker/
├── app.py
├── requirements.txt
├── Dockerfile
├── templates/
│   ├── index.html
│   └── update.html
├── .gitignore
```

---



## 👤 Author

**Vandrangi Sandeep**  
📧 sandeepvandrangi@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sandeep-vandrangi-dev)

---

