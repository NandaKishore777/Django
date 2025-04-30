# Django
# 📝 Django Notes App

A clean and minimal Django project that allows authenticated users to create, edit, and delete their personal notes. Built from scratch as part of a Day 1 learning project, this app demonstrates the fundamentals of Django's MVT architecture, user management, and CRUD functionality.

## 🚀 Features

- 🔐 User Authentication (Signup, Login, Logout)
- 🧠 User-specific notes (only the logged-in user can view their notes)
- ✏️ Create, Read, Update, Delete notes
- 📅 Notes are timestamped by creation
- 🎨 Minimal templates using Django Template Language (DTL)

## 🏗️ Tech Stack

- Python 3.10+
- Django 4.x
- SQLite3 (default database)
- HTML/CSS (basic styling)

## 📁 Project Structure

```
myproject/
├── myapp/
│   ├── migrations/
│   ├── templates/
│   │   ├── home.html
│   │   └── edit.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── myproject/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── manage.py
```

## 📌 Installation

```bash
git clone https://github.com/yourusername/django-notes-app.git
cd django-notes-app
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## 🧪 Usage

1. Visit `http://127.0.0.1:8000/`
2. Sign up / Log in
3. Add your notes securely
4. Edit or delete them as needed

## 🔐 Security
- Uses Django's built-in user authentication
- Prevents access to other users' data via query filtering and decorators

## 📄 License
MIT License. Feel free to fork and extend it.

---

### ✍️ Author
**Nanda Kishore** – (https://www.linkedin.com/in/nandakishore7) | [GitHub](https://github.com/NandaKishore777)

---

> Learning Django by building. From Day 1, solving real problems.
