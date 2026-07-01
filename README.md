# Django-Twite

🐦 Django Twite

A basic Twitter-like web application built using the Django framework. This project was created for learning the fundamentals of Django, including project setup, models, views, templates, URL routing, and basic CRUD operations.

📖 About the Project

Django Twite is a beginner-friendly practice project that allows users to create, view, edit, and delete short text posts (tweets). The main objective of this project is to understand the core concepts of Django and how different components work together to build a web application.

This project is intended for educational purposes and demonstrates the basic workflow of a Django application.


✨ Features

Create a Tweet
View All Tweets
Edit Existing Tweets
Delete Tweets
Simple User Interface
Django Template Rendering
Basic CRUD Operations


🛠️ Technologies Used

1. Backend
Python
Django

2. Frontend
HTML5
Tailwind CSS
CSS3

3. Database
SQLite3 (Default Django Database)


📂 Project Structure

Django-Twite/
│
├── twite/                 # Main Django Application
├── templates/             # HTML Templates
├── static/                # CSS and Static Files
├── manage.py              # Django Management File
├── db.sqlite3             # SQLite Database
├── requirements.txt       # Project Dependencies
├── README.md
└── .gitignore


⚙️ Installation

1. Clone the Repository
git clone https://github.com/JaiminJarsaniya/Django-Twite.git

2. Navigate to the Project Folder
cd Django-Twite

3. Create a Virtual Environment
python -m venv venv
Windows
venv\Scripts\activate
Linux / macOS
source venv/bin/activate

4. Install Required Packages
pip install -r requirements.txt

5. Apply Database Migrations
python manage.py migrate

6. Run the Development Server
python manage.py runserver

Open your browser and visit:

http://127.0.0.1:8000/
