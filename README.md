# Django Learning Project 🚀

A hands-on Django project built while learning the Django web framework. This project covers the fundamentals of Django — project setup, URL routing, views, templates, and serving static files.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Framework:** Django 6.0.6
- **Database:** SQLite3 (default)
- **Server:** Django Development Server
- **Environment:** Virtual Environment (`venv`)

---

## 📁 Project Structure

```
Django/
├── mysite/
│   ├── __init__.py
│   ├── asgi.py
│   ├── wsgi.py
│   ├── settings.py
│   ├── urls.py
│   └── views.py
├── templates/
│   └── home.html
├── manage.py
└── requirements.txt
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate        # On macOS/Linux
venv\Scripts\activate           # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Run the development server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

---

## 📌 Features Covered So Far

- [x] Django project setup using `django-admin startproject`
- [x] URL routing via `urls.py`
- [x] Function-based views in `views.py`
- [x] Template rendering with `render()`
- [x] Custom templates directory configuration in `settings.py`
- [x] Django development server

---

## 📚 What I'm Learning

- Django's MVT (Model-View-Template) architecture
- URL dispatcher and named routes
- Django template language (DTL)
- Django ORM and models
- Static files and media handling
- Django Admin panel

---

## 🔒 Notes

- `DEBUG = True` is for development only — never use in production.
- `venv/`, `db.sqlite3`, `.env`, and `__pycache__/` are excluded via `.gitignore`.

---

## 👨‍💻 Author

**Devang Saini**  
Learning Django — one `runserver` at a time.
