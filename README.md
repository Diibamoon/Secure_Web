# Secure_Web
Secure Web Management System using Django
# Secure Task Management System

This project is a secure web-based task management system developed using Django as part of the Secure Software Development course.

## Installation Steps

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
User
1. Create Username and Password
<img width="1161" height="871" alt="6" src="https://github.com/user-attachments/assets/87ecd159-4093-4cd0-b161-1e92fbf20886" />
2. Log in to the account user
<img width="1160" height="875" alt="1" src="https://github.com/user-attachments/assets/1d14f282-da5e-4083-8cba-81fd897b6e7a" />
3. You will see your account and the details 
<img width="1162" height="873" alt="2" src="https://github.com/user-attachments/assets/e6297f4c-17f0-4af7-97a9-1e7e3a8ff51e" />
4. User manage to edit and delete the tasks
<img width="1162" height="876" alt="3" src="https://github.com/user-attachments/assets/3a641e51-0c70-43a7-8fcc-eaacaaa5c1b6" />
5. The task has been successfully deleted
<img width="1162" height="875" alt="4" src="https://github.com/user-attachments/assets/fb589e23-4a89-4552-b29c-b7091b59b977" />
<img width="1162" height="872" alt="9" src="https://github.com/user-attachments/assets/9a2adf56-e0a1-4260-ad9d-4409620193e8" />


Admin
<img width="1163" height="872" alt="5" src="https://github.com/user-attachments/assets/8918256a-8a07-4590-910c-90b361bfb5ec" />
<img width="1160" height="875" alt="7" src="https://github.com/user-attachments/assets/7a9b192c-f863-4641-90cf-fd1c094c7eb2" />
<img width="1165" height="873" alt="8" src="https://github.com/user-attachments/assets/c5ed4015-4e8d-4e5a-9e5d-a84d2f0b7706" />

