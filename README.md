# Complaint Management System

A role-based web application built with Django for submitting, managing, assigning, tracking, and resolving complaints within an organization.

## 🚀 Features

* 👤 Role-based access for Users, Staff, and Admins
* 📝 Create and submit complaints
* 🔍 Search and filter complaints
* 📊 Complaint status tracking
* 👨‍💼 Assign complaints to staff members
* 💬 Complaint-related chat and communication
* 📎 File and document upload support
* 📈 Admin dashboard and complaint management
* 🔐 Secure user authentication and role-based permissions
* 📱 Responsive web interface

## 👥 User Roles

### User

* Submit new complaints
* View submitted complaints
* Track complaint status
* Communicate regarding complaints
* Upload supporting files

### Staff

* View assigned complaints
* Update complaint status
* Communicate with users
* Manage complaints assigned to them

### Admin

* Manage users and staff
* Assign complaints
* Monitor complaint progress
* View complaint statistics and reports
* Manage the overall system

## 🛠️ Tech Stack

* **Backend:** Python, Django
* **Frontend:** HTML, CSS, JavaScript
* **Database:** SQLite
* **Authentication:** Django Authentication System
* **Deployment:** Render

## 🏗️ Application Workflow

```text
User
  │
  ▼
Submit Complaint
  │
  ▼
Admin Reviews Complaint
  │
  ▼
Assigns to Staff
  │
  ▼
Staff Handles Complaint
  │
  ▼
Status Updated
  │
  ▼
Complaint Resolved
```

## 📂 Project Structure

```text
Complaint-Management-System/
│
├── cms_project/          # Django project configuration
├── complaints/           # Main application
├── staticfiles/          # Static files
├── manage.py             # Django management script
├── requirements.txt      # Python dependencies
├── .gitignore
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/saketh1106/Complaint-Management-System.git
cd Complaint-Management-System
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

Open the application at:

```text
http://127.0.0.1:8000/
```

## 🌐 Live Demo

**Coming soon**

## 📸 Screenshots

Screenshots of the application will be added here.

## 🔮 Future Improvements

* Email notifications for complaint updates
* Advanced reporting and analytics
* Improved real-time communication
* Cloud-based file storage
* Additional organization-level management features

## 📄 License

This project was developed as an academic and portfolio project.
