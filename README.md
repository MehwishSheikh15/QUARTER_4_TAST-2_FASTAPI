# Task 2 - Day 2: FastAPI Project (Generative AI Learning)

## Student Information

- **Name:** MEHWISH SHEIKH
- **Course:** Generative AI Learning
- **Task:** Task 2 of Day 2

---

## 📄 Description

This project is a simple **FastAPI** application built as part of Task 2 of Day 2 in the Generative AI learning program.

The app includes:

- A **root route** (`/`) that returns a Hello World message.
- An **items route** (`/items/{item_id}`) that returns item details with optional query parameters.

---

## 💻 Requirements

- Python 3.13
- FastAPI
- Uvicorn

---

## 📦 Setup Instructions

1. **Clone the repository or download the code**

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
Activate the virtual environment

On Windows:

bash
Copy
Edit
.venv\Scripts\Activate.ps1
On macOS/Linux:

bash
Copy
Edit
source .venv/bin/activate
Install dependencies

bash
Copy
Edit
pip install fastapi uvicorn
Run the FastAPI app

bash
Copy
Edit
uvicorn main:app --reload
Access in browser

API root: http://127.0.0.1:8000

API docs: http://127.0.0.1:8000/docs

✨ Features
✅ FastAPI app with two routes

✅ Run and test locally

✅ Explore API using Swagger UI

📚 Learning Reflection
Through this task, I learned how to:

Set up a FastAPI project

Define routes and handle query parameters

Run the app using Uvicorn

Use virtual environments and install dependencies

✅ Commands Summary
bash
Copy
Edit
git init
git add .
git commit -m "Initial commit"
📩 Notes
This README is part of the submission for Task 2 (Day 2) of the Generative AI learning program.
