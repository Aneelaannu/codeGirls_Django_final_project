# codeGirls_Django_final_project
Step-by-step: Create Django Project "sms" (All files & settings) 
# Create venv (Windows)
python -m venv venv
venv\Scripts\activate



Step 1: Install Django
pip install django python-docx
# (python-docx is needed only to generate this Word file programmatically; skip if you don't need it)
Step 2: Create Django project and app
Run these commands in your terminal/command prompt:
django-admin startproject techcenter
cd sms
python manage.py startapp mainapp

Step 3: Project structure
After creating the project and app, your folder structure should look like:
sms/
├── manage.py
├── sms/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── mainapp/   
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    ├── views.py
    ├── forms.py     # create this file
    └── templates/   # create this folder and files inside

