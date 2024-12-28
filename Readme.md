# Task Manager - Simple Django Project

**Task Manager** is a basic Django project to manage tasks, allowing users to create, view, and delete tasks through Django's admin interface and basic views.

## Features
- Add new tasks
- View a list of all tasks
- Delete tasks

## Technologies Used
- Python 3.x
- Django 4.x
- SQLite (default Django database for simplicity)

---

## Installation Guide

### Prerequisites
- Python 3.x installed
- Virtual environment tool (recommended)

### Steps

#### 1. Clone the repository
```bash
git clone https://github.com/sumitnagpure/task-manager.git
cd task-manager
```

#### 2. Set up a virtual environment
For Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```
For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

#### 3. Install dependencies
```bash
pip install -r requirements.txt
```

#### 4. Run database migrations
```bash
python manage.py migrate
```

#### 5. Create a superuser (for admin access)
```bash
python manage.py createsuperuser
```

#### 6. Start the development server
```bash
python manage.py runserver
```

Access the application at `http://127.0.0.1:8000/`.

---

## Basic Usage

### 1. Admin Interface
Go to `http://127.0.0.1:8000/admin/` and log in with your superuser credentials to manage tasks.

### 2. Task Views
- **Add Task**: Use the admin interface to add tasks.
- **View Tasks**: Access the task list at `http://127.0.0.1:8000/tasks/`.
- **Delete Tasks**: Delete tasks using the available delete buttons in the task list view.

---

## License
This project is licensed under the MIT License.

---

## Acknowledgments
- Django framework

---

Enjoy managing your tasks with Task Manager! 🚀
