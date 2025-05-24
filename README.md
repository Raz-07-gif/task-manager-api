# 📝 Task Manager API

A simple backend API built with Flask and SQLite for managing tasks using CRUD operations.

---

## 🚀 Features

- ✅ Create new tasks
- 📋 View all tasks
- ✏️ Update existing tasks
- ❌ Delete tasks

---

## 🧰 Tech Stack

- Python 3
- Flask
- Flask-SQLAlchemy
- SQLite
- Postman (for API testing)

---

## 📁 Setup Instructions

1. Clone this repo  
   `git clone https://github.com/your-username/task-manager-api.git`

2. Navigate into the folder  
   `cd task_manager`

3. Create a virtual environment  
   `python -m venv venv`

4. Activate the virtual environment  
   - Windows: `venv\Scripts\activate`
   - Linux/Mac: `source venv/bin/activate`

5. Install requirements  
   `pip install -r requirements.txt`

6. Run the app  
   `python app.py`

7. Visit `http://127.0.0.1:5000/tasks` in Postman to test.

---

## 📬 API Endpoints

| Method | Endpoint           | Description        |
|--------|--------------------|--------------------|
| GET    | `/tasks`           | List all tasks     |
| POST   | `/task`            | Create a task      |
| PUT    | `/task/<id>`       | Update a task      |
| DELETE | `/task/<id>`       | Delete a task      |

---
Sample POST body JSON
{
  "title": "Learn Flask"
}
Sample PUT body JSON
{
  "title": "Update Flask Task",
  "done": true
}


## 📚 License

Open-source for educational use. Customize as needed.
