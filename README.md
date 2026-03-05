# FastAPI Notes API

A simple **Notes CRUD API** built using **FastAPI**, **SQLAlchemy**, and **SQLite**.
This project allows users to create, read, update, and delete notes through REST APIs.

## 🚀 Live API

Backend is deployed on Render:

https://fastapi-backend-nvwe.onrender.com

API Documentation:

https://fastapi-backend-nvwe.onrender.com/docs

Alternative Docs:

https://fastapi-backend-nvwe.onrender.com/redoc

---

## 🛠 Tech Stack

* FastAPI
* Python
* SQLAlchemy
* SQLite
* Uvicorn
* Render (Deployment)

---

## 📁 Project Structure

```
fastapi-backend
│
├── app
│   ├── routers
│   │   └── notes.py
│   ├── database.py
│   ├── models.py
│   └── schemas.py
│
├── notes.db
├── requirements.txt
└── README.md
```

---

## ⚡ API Endpoints

### Get All Notes

```
GET /notes/
```

### Get Single Note

```
GET /notes/{note_id}
```

### Create Note

```
POST /notes/
```

Body:

```
{
"title": "My Note",
"content": "Hello world"
}
```

### Update Note

```
PUT /notes/{note_id}
```

### Delete Note

```
DELETE /notes/{note_id}
```

---

## 🧪 Run Locally

Clone the repository:

```
git clone https://github.com/ParthAgarwal8619/fastapi-backend.git
```

Go to project folder:

```
cd fastapi-backend
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the server:

```
uvicorn app.main:app --reload
```

Open in browser:

```
http://127.0.0.1:8000/docs
```

---

## 🌐 Deployment

Backend deployed using **Render**.

Live URL:

https://fastapi-backend-nvwe.onrender.com

---

## 📌 Features

* Create Notes
* Read Notes
* Update Notes
* Delete Notes
* Interactive API docs
* CORS enabled for frontend

---

## 👨‍💻 Author

Parth Agarwal

GitHub:
https://github.com/ParthAgarwal8619
