# To-Do API with FastAPI

A simple To-Do REST API built with FastAPI, SQLAlchemy, and JWT Authentication.  
It provides user registration, login, and task management (CRUD).  
Interactive API documentation is available via Swagger UI at `/docs`.

---

## Features

- User registration and login with JWT tokens
- Create, Read, Update, Delete tasks
- Secure endpoints requiring authentication
- Interactive API documentation via Swagger UI

---

## Tech Stack

| Component | Technology           |
| --------- | -------------------- |
| Language  | Python 3.8+          |
| Framework | FastAPI              |
| Database  | SQLite (default)     |
| ORM       | SQLAlchemy           |
| Auth      | JWT (JSON Web Token) |
| Docs      | Swagger UI (auto)    |

---

## Installation & Setup

```bash
git clone https://github.com/softwarjx/todo-api-fastapi.git
cd todo-api-fastapi
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
http://127.0.0.1:8000/docs

---

## Screenshots

	1.	Register User – /register
Shows the curl request and successful response (200 OK).
	2.	Login User – /login
Shows the access_token returned on successful login.
	3.	Create Task – /tasks (POST)
Shows creating a new task, response includes task id and owner_id.
	4.	View Tasks – /tasks (GET)
Shows retrieving all tasks for the authenticated user.

⸻

License

MIT License – feel free to use and modify for learning or production purposes.

⸻

Author: softwarjx
```
