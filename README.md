# 📝 ToDo Web App using Django

A simple and intuitive ToDo web application built using the Django framework. This app allows users to register, log in, and manage their personal tasks efficiently with a user-friendly interface.

---

## 🚀 Features

- User authentication (Register / Login / Logout)
- Create, update, and delete tasks
- Mark tasks as complete/incomplete
- Set task due dates
- Filter tasks by status
- Responsive UI using HTML, CSS, and Bootstrap
- Admin dashboard for managing users and tasks

---

## 🖥️ Screenshots

> *(Add your screenshots to a `screenshots/` folder in your repo and replace these file names)*

![Home Page](screenshots/home.png)  
![Task List](screenshots/tasklist.png)  
![Add Task](screenshots/addtask.png)

---

## 🛠️ Technologies Used

- Python 3.x  
- Django 4.x  
- SQLite (default Django DB)  
- HTML, CSS, Bootstrap  
- JavaScript (optional)

---

## 📦 Installation Guide

Follow these steps to run the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/ToDo-webapp-using-Django.git
   cd ToDo-webapp-using-Django
Create a virtual environment
python -m venv venv

Activate the environment

On Windows:venv\Scripts\activate
On macOS/Linux:source venv/bin/activate

Install dependencies
python manage.py migrate

Run the development server
python manage.py runserver

Open in browser
Visit: http://127.0.0.1:8000/



🧪 Running Tests
To run unit tests, use:
python manage.py test
