# 🚀 CollabTrack - Project Management Platform

> A modern **Jira-inspired Project Management Platform** built with **Django, Django REST Framework, and PostgreSQL** that helps teams organize projects, manage tasks, collaborate efficiently, and monitor progress through an interactive dashboard.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Django](https://img.shields.io/badge/Django-Framework-green?style=for-the-badge&logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge&logo=bootstrap)
![DRF](https://img.shields.io/badge/Django-REST%20Framework-red?style=for-the-badge)

---

# 📌 Overview

Project Management Platform is a collaborative web application that enables teams to efficiently manage projects, assign tasks, monitor progress, and improve productivity.

The application includes authentication, project and task management, team collaboration, analytics dashboard, search functionality, and REST APIs for seamless integration.

---

# ✨ Features

## 👤 Authentication & User Management

- User Registration
- Secure Login & Logout
- User Profile Management
- Change Password
- Session Authentication

---

## 📁 Project Management

- Create Projects
- Update Project Details
- Delete Projects
- View Project Information
- Add Multiple Team Members
- Manage Project Ownership

---

## ✅ Task Management

- Create Tasks
- Edit Tasks
- Delete Tasks
- Assign Tasks to Team Members
- Set Task Priority

  - High
  - Medium
  - Low

- Update Task Status

  - Pending
  - In Progress
  - Completed

- Due Date Tracking

---

## 📊 Interactive Dashboard

Get an instant overview of your workspace.

Dashboard includes:

- 📌 Total Projects
- ✅ Completed Tasks
- ⏳ Pending Tasks
- 📋 Total Tasks
- 🕒 Recent Activities
- 📈 Progress Charts (Chart.js)

---

## 🔍 Search & Filtering

Quickly find information with:

### Project Search

- Search by project name

### Task Search

- Search by task title

### Filters

- Status Filter
- Priority Filter

---

# 🔐 Security

- Django Authentication System
- Login Required Views
- Role-Based Permissions
- Task Assignment Restrictions
- Protected CRUD Operations
- CSRF Protection

---

# 🌐 REST API

Built using **Django REST Framework (DRF)**

## Projects API

| Method | Endpoint | Description |
|------------|----------------|----------------|
| GET | `/api/projects/` | Get all projects |
| POST | `/api/projects/` | Create project |
| PUT | `/api/projects/<id>/` | Update project |
| DELETE | `/api/projects/<id>/` | Delete project |

---

## Tasks API

| Method | Endpoint | Description |
|------------|----------------|----------------|
| GET | `/api/tasks/` | Get all tasks |
| POST | `/api/tasks/` | Create task |
| PUT | `/api/tasks/<id>/` | Update task |
| DELETE | `/api/tasks/<id>/` | Delete task |

---

# 🛠 Tech Stack

## Backend

- Python
- Django
- Django REST Framework

## Database

- PostgreSQL

## Frontend

- HTML5
- Bootstrap 5
- CSS3
- JavaScript
- Chart.js

---

# 📂 Project Structure

```
project-management-system/
│
├── accounts/
├── projects/
├── tasks/
├── dashboard/
├── api/
├── templates/
├── static/
├── core/
├── manage.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone [https://github.com/HJB0810/project-management-system.git](https://github.com/vaibhavi-development-project/CollabTrack.git )

cd project-management-system
```

---

## 2. Create Virtual Environment

```bash
python -m venv env
```

---

## 3. Activate Virtual Environment

### Windows

```bash
env\Scripts\activate
```

### Linux / macOS

```bash
source env/bin/activate
```

---

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5. Configure PostgreSQL Database

Update the database settings inside:

```
settings.py
```

Example:

```python
DATABASES = {
    "default": {
        "ENGINE": "django.db.backends.postgresql",
        "NAME": "project_db",
        "USER": "postgres",
        "PASSWORD": "your_password",
        "HOST": "localhost",
        "PORT": "5432",
    }
}
```

---

## 6. Apply Migrations

```bash
python manage.py makemigrations

python manage.py migrate
```

---

## 7. Create Superuser (Optional)

```bash
python manage.py createsuperuser
```

---

## 8. Run Development Server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

---

# 📸 Screenshots

You can add screenshots here.

```
screenshots/
│
├── dashboard.png
├── login.png
├── project-list.png
├── task-list.png
└── api.png
```

Example:

```markdown
## Dashboard

![Dashboard](screenshots/dashboard.png)

## Projects

![Projects](screenshots/project-list.png)
```

---

# 🎯 Future Enhancements

- 🔔 Real-time Notifications
- 📎 File Attachments
- 📧 Email Alerts
- 🗂 Kanban Board
- 📝 Activity Logs
- 💬 Team Comments
- 📅 Calendar View
- 🔄 Drag & Drop Task Management
- 🌙 Dark Mode
- ☁ Deployment on Render / Railway / Docker

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Add new feature"
```

4. Push the branch

```
git push origin feature-name
```

5. Open a Pull Request

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and motivates future improvements.

---

# 👨‍💻 Author

**Vaibhavi Dave**

GitHub: **https://github.com/vaibhavi-development-project**

---

## License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute it for learning and development purposes.
