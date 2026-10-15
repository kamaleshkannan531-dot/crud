# Student Management System (Django CRUD)

A simple, functional CRUD (Create, Read, Update, Delete) web application built with Python and Django to manage student records.

---

## 🚀 Features

- **View Students:** List all registered students in a responsive table.
- **Add Student:** Form to insert new student details (Name, Email, Department).
- **Edit Student:** Update existing student information with pre-filled forms.
- **Delete Student:** Remove student records with confirmation protection.
- **Django Admin Integration:** Full admin panel access to view and manage students.

---

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Database:** SQLite (default Django database)
- **Frontend:** HTML5, CSS

---

## 📁 Project Structure

```text
crudproject/
│
├── crudapp/                      # Core application
│   ├── migrations/               # Database migration files
│   ├── templates/                # HTML templates
│   │   ├── student_form.html     # Add/Edit student form
│   │   └── student_list.html     # List all students table
│   ├── admin.py                  # Admin configuration
│   ├── apps.py                   # App configuration
│   ├── models.py                 # Student data model
│   ├── urls.py                   # App-level routing
│   └── views.py                  # CRUD views logic
│
├── crudproject/                  # Main project directory
│   ├── settings.py               # Project settings
│   ├── urls.py                   # Root URL configuration
│   └── wsgi.py                   # WSGI configuration
│
├── .gitignore                    # Ignored files (venv, db, cache)
├── manage.py                     # Django management script
└── README.md                     # Project documentation
