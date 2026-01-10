# Secure_Web
Secure Web Management System using Django
# Secure Task Management System

This project is a secure web-based task management system developed using Django as part of the Secure Software Development course.

## Installation Steps
1. Clone the repository
2. Create a virtual environment
3. Install dependencies:
4. Create `.env` file based on `.env.example`
5. Run migrations:
6. Run server:
   
## Features
- User registration and authentication
- Role-Based Access Control (Admin & User)
- Secure CRUD operations for tasks
- Audit logging for security events
- OWASP Top 10 security controls implemented

## Security Features
- Password hashing (PBKDF2)
- CSRF protection
- Input validation
- Access control enforcement
- Audit logs (admin only)

## How to Run the Application

### Prerequisites
- Python 3.10 or above
- pip (Python package manager)
- Visual Studio Code (VS Code)

### Steps to Run

1. Clone the repository:
   https://github.com/Diibamoon/Secure_Task_Manager_Web.git
2. Extract file to desktop (filename: secure_web)
3. Open Visual Studio Code (VS Code).
4. Open "secure_web" project folder in VS Code.
5. Run the Project in terminal : "cd secure_web"
6. Run command "pip install django"
7. Run command "pip install pyhton-dotenv"
8. Run command "python manage.py runserver"
9. Open browser "https://127.0.0.1:8000/login/"

Once the Web Application appear http://127.0.0.1:8000/login/

1. Register username and creat password.
2. Login in to account.
3. Complete your tasks.
4. What you can see in the system as User are:
   - Details of your infomation
   - Edit and delete tasks
5. In the same web and account try to log in to audit log as User http://127.0.0.1:8000/audit-log/
6. It is Forbidden
7. What you can see in the system as Admin are:
   - User log in lists
   - Authorise/ staff person
   - Manage User accounts
   - Manage to see audit log with Users' Username, Action and Timestamp.
8. In the same web and account try to log in to audit log as Admin http://127.0.0.1:8000/audit-log/
9. You will get to see the Audit Log

---
### Default Roles
- **Admin**: Can view audit logs and manage users
- **Normal User**: Can manage personal tasks only

## Dependencies
- Django
- Python 3.x

## Screenshots
<img width="1160" height="875" alt="1" src="https://github.com/user-attachments/assets/ac82a02f-6c9e-49e1-93f3-cd5b21d6bf8d" />
<img width="1162" height="873" alt="2" src="https://github.com/user-attachments/assets/18a77893-a167-42d6-91f2-fffc9bceebb9" />
<img width="1162" height="876" alt="3" src="https://github.com/user-attachments/assets/b91bee40-4412-4462-b7a5-1c0373dad37c" />
<img width="1162" height="875" alt="4" src="https://github.com/user-attachments/assets/00f3047f-6ac5-4f86-bded-98863ba40638" />
<img width="1163" height="872" alt="5" src="https://github.com/user-attachments/assets/965edf36-c0b6-4b9c-a3f8-cedd59e99fad" />
<img width="1161" height="871" alt="6" src="https://github.com/user-attachments/assets/8905f591-02b2-4406-a8eb-66c4f3b3d635" />
<img width="1160" height="875" alt="7" src="https://github.com/user-attachments/assets/35183a49-cbc8-4a1e-b071-fdcd4a8f96bb" />
<img width="1165" height="873" alt="8" src="https://github.com/user-attachments/assets/0eb4fa52-6c59-417e-8f92-49c1ffb1108b" />
<img width="1162" height="872" alt="9" src="https://github.com/user-attachments/assets/5142933e-80af-4a82-aded-7b6b2e9a86b9" />

