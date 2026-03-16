**Django Portfolio Website

**A personal portfolio website built using Django to showcase projects, skills, and contact information.

**Features**

Personal portfolio homepage

Project showcase section

About section

Contact form

Admin panel for managing content

Responsive design


**Tech Stack**

Python

Django

HTML5

CSS3

Bootstrap

SQLite (default Django database)


**Project Setup**
1. Clone the Repository

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

2. Create Virtual Environment

python -m venv venv

3. Activate Virtual Environment

Windows

3. Activate Virtual Environment

Windows

venv\Scripts\activate

Linux / Mac

source venv/bin/activate

4. Install Dependencies

pip install -r requirements.txt

5. Apply Migrations

python manage.py makemigrations
python manage.py migrate

6. Create Superuser (Admin)

python manage.py createsuperuser

7. Run the Development Server

python manage.py runserver


**portfolio/**
│
├── portfolio/        # Main project folder
├── app/              # Portfolio application
├── templates/        # HTML templates
├── static/           # CSS, JS, images
├── db.sqlite3        # Database
├── manage.py
└── requirements.txt
