# Django MySQL Project Setup

This guide explains how to set up the project on your local machine.

---

## 1. Create a Virtual Environment

Run this command to create a virtual environment (you can choose any name):

```bash
py -m venv venv

2. Activate the Virtual Environment

Windows:

.\venv\Scripts\activate

Linux / MacOS:

source venv/bin/activate



3. Install Required Packages

Install Django, django-environ, and MySQL client:

pip install django
pip install django-environ
pip install mysqlclient



4. Configure .env File

Create a .env file in the project root (you can copy .env.example):

SECRET_KEY=your-secret-key-here
DEBUG=True
NAME=your-database-name
USER=your-database-username
PASSWORD=your-database-password
HOST=localhost
PORT=3306


6. Run the Project
python manage.py migrate
python manage.py runserver


