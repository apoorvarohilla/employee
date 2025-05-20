🛠 Employee Management System (Django)
A Django-based API system for managing Employees, Departments, Attendance & Performance, with Swagger docs and optional charts.

🚀 Features
CRUD APIs using Django REST Framework

JWT Authentication

Swagger UI for API docs

Fake data seeding using Faker

Optional: Chart.js visualizations & Docker support

⚙️ Tech Stack
Django 4.x, DRF

PostgreSQL

drf-yasg, django-environ, Faker

Optional: Chart.js, Docker

📦 Setup
bash
Copy
Edit
git clone https://github.com/your-username/employee-management.git
cd employee-management
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # Fill DB credentials
python manage.py migrate
python manage.py seed_data
python manage.py runserver
Swagger: http://localhost:8000/swagger/
Charts (optional): http://localhost:8000/charts/

📁 API Endpoints
Endpoint	Description
/api/employees/	Employee CRUD
/api/departments/	Department CRUD
/api/attendance/	Attendance CRUD
/api/performance/	Performance CRUD
/api/token/	Get JWT Token

🐳 Docker (Optional)
bash
Copy
Edit
docker-compose up --build
📌 Bonus Ideas
Role-based access (Admin, HR)

Unit tests for APIs

UI with Django templates

📄 License
For demo/learning purposes.

