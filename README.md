# Student Management System
### Django-Based CRUD Web Application

A structured and scalable Student Management System built using **Python and Django**, implementing complete **CRUD (Create, Read, Update, Delete)** operations with proper database integration and clean architectural design.

This project demonstrates backend development fundamentals using Django’s Model–Template–View (MTV) framework and relational database management.

---

## 1. Executive Summary

The Student Management System is a web-based application that enables efficient management of student records.

The system allows administrators to:

- Create new student entries  
- View student records  
- Update existing student information  
- Delete student records  

This project highlights practical implementation of Django models, forms, views, templates, and ORM-based database operations.

---

## 2. Objectives

The primary objectives of this project are:

- Demonstrate CRUD functionality using Django  
- Apply MVC/MTV architectural principles  
- Integrate relational database management  
- Implement form handling and validation  
- Maintain clean and scalable project structure  

---

## 3. Key Features

- Add student records  
- Display student list  
- Update student information  
- Delete student records  
- Django ORM integration  
- Form validation  
- Structured URL routing  
- Clean and maintainable codebase  

---

## 4. Technology Stack

### Backend
- Python
- Django Framework

### Database
- SQLite (default Django database)

### Frontend
- HTML
- CSS
- Django Template Engine

### Development Tools
- Git
- GitHub
- Virtual Environment (venv)

---

## 5. System Architecture

This application follows Django’s MTV (Model–Template–View) architecture:

- **Model** – Defines database schema and structure  
- **Template** – Handles user interface rendering  
- **View** – Processes business logic and request handling  
- **URL Configuration** – Manages routing between components  

This separation ensures scalability, maintainability, and clarity of responsibilities.

---

## 6. Project Structure

```
Student-Management-System/
│
├── manage.py
├── db.sqlite3
│
├── student_management/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
└── students/
    ├── models.py
    ├── views.py
    ├── forms.py
    ├── urls.py
    ├── admin.py
    └── templates/
```

---

## 7. Installation & Setup

### Prerequisites

- Python 3.8+
- pip
- Virtual environment (recommended)

---

### Step 1: Clone the Repository

```bash
git clone https://github.com/asimmagar20/Student-Management-System.git
```

---

### Step 2: Navigate to Project Directory

```bash
cd Student-Management-System
```

---

### Step 3: Create Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows**
```bash
venv\Scripts\activate
```

**macOS / Linux**
```bash
source venv/bin/activate
```

---

### Step 4: Install Dependencies

If `requirements.txt` is available:

```bash
pip install -r requirements.txt
```

Otherwise install Django manually:

```bash
pip install django
```

---

### Step 5: Apply Migrations

```bash
python manage.py migrate
```

---

### Step 6: Run Development Server

```bash
python manage.py runserver
```

The application will run at:

```
http://127.0.0.1:8000/
```

---

## 8. Application Workflow

1. User accesses the application  
2. Administrator adds student details  
3. Data is stored in SQLite database  
4. Records can be updated or deleted  
5. Changes are handled dynamically using Django ORM  

---

## 9. Learning Outcomes

This project demonstrates understanding of:

- Django project setup and configuration  
- Model creation and database migrations  
- Form handling and validation  
- URL routing  
- Template rendering  
- CRUD operations  
- Backend development best practices  

---

## 10. Future Enhancements

- User authentication and authorization  
- Role-based access control  
- Search and filtering functionality  
- Pagination  
- REST API implementation using Django REST Framework  
- PostgreSQL integration  
- Deployment to cloud platforms  

---

## 11. Author

**Asim Pun Magar**  
GitHub: https://github.com/asimmagar20  

---

## 12. License

This project is open-source and available under the MIT License.
