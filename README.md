# 📝 Django Blog (Early Version)

This was one of my first attempts at building a blog using Django — a beginner-friendly project to learn the Django framework, how views, models, and templates work, and to understand the basics of web development.

> ⚠️ Note: This is a work-in-progress / learning project, not a production-ready app.

## 📚 What I Learned

- Setting up a Django project and apps
- Creating models, views, and templates
- Basic admin interface customization
- Routing using `urls.py`
- Understanding Django’s project structure

## 🛠️ Stack

- Python 3.x
- Django 4.x
- SQLite (default dev database)
- HTML + CSS (Django templating)

## ▶️ How to Run

1. Clone the repo:

```bash
git clone https://github.com/benjamaina/django-blog.git
cd django-blog
Set up virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt  # or manually install Django
Run the server:

bash
Copy
Edit
python manage.py migrate
python manage.py runserver
Access the app at http://127.0.0.1:8000

🚀 Future Goals 
Add user authentication (register/login/logout)

Enable blog post creation from frontend

Add comments and tags

Use class-based views

REST API support with Django REST Framework
