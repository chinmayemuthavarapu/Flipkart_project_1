 # Leave Management System
>  Built by * Muthavarapu chinmaye chowdary* for Flipkart Task-1  
> 🗓 Last Updated: *31 July 2025*
A comprehensive web-based Leave Management System built with Flask, SQLAlchemy, and modern HTML/CSS.
## Overview
-
The Employee Leave Management System (ELMS) is a comprehensive web application designed to streamline and automate the process of managing employee leave requests. It provides features for employees to request leave, managers to approve/reject requests, and administrators to manage the system and generate reports.
---
## Features
- *User Authentication*: Secure login for employees, managers, and administrators
- *User Roles:* Admin, Manager, and Employee with different permissions
- *Leave Request Workflow:* Submit, approve, reject, and cancel leave requests
- *Dashboard:* Overview of leave statistics and recent requests
- *User Management:* Admin can create and manage users
- *Responsive Design:* Works on desktop and mobile devices
---
## Technology Stack
- *Frontend*: HTML5, CSS3, JavaScript, Bootstrap 5
- *Backend*: Python, Flask
- *Database*: SQLite (with SQLAlchemy ORM)
- *Authentication*: Flask-Login
- *Reporting:* CSV, PDF generation

## Installation
1. Clone the repository:
   bash
 https://github.com/velpuribhargavi/Flipkart-_project.git
   
2. Create and activate a virtual environment:
   bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   
3. Install dependencies:
   bash
   pip install -r requirements.txt
   
4. Initialize the database:
  bash
      python app.py

5. Run the application:
   bash
   python app.py
   
6. Access the application at :http://localhost:127.0.0.1:5000

---
## Default Users
The system creates default users when first initialized:

- Admin:
      Username: admin
      Password: admin123
- Manager:
      Username: manager
      Password: man123
- Employee:
      Username: employee
      Password: emp123

---
## Project Structure

bash
leave-management-system/
├── app.py                 # Main application file
├── templates/             # HTML templates
│   ├── _flash_messages.html
│   ├── _leave_status_badge.html
│   ├── _pagination.html
│   ├── 404.html
│   ├── 500.html
│   ├── base.html
│   ├── change_password.html
│   ├── dashboard.html
│   ├── leave_requests.html
│   ├── login.html
│   ├── new_leave_request.html
│   ├── new_user.html
│   ├── profile.html
│   ├── reports.html
│   ├── users.html
│   └── view_leave_request.html
├── README.md              # This file
└── requirements.txt       # Python dependencies

---

## Individual Features 

### Employee Features
- View leave balances
- Submit new leave requests
- Track request status
- View request history

### Manager Features
- Approve/reject leave requests
- View team leave calendar
- Monitor pending approvals

### Admin Features
- Manage all users
- Configure leave types
- Generate system reports
- Monitor system activity
---
## Screenshots

- # admin_manager
<img width="1280" height="569" alt="admin_Image"
 src=" https://github.com/chinmayemuthavarapu/Flipkart_project_1/blob/main/admin_manager.jpg?raw=true"/>

- # Manager_Profile
<img width="2080" height="568" alt="Image" 
src=" https://github.com/chinmayemuthavarapu/Flipkart_project_1/blob/main/manager_profile.jpg?raw=true" />

 - # leave_request
  <img width="1280" height="570" alt="Image" 
src=" https://github.com/chinmayemuthavarapu/Flipkart_project_1/blob/main/leave_request.jpg?raw=true"/>

- # employe_leaveRequest
    <img width="1280" height="521" alt="Image" 
src=" https://github.com/chinmayemuthavarapu/Flipkart_project_1/blob/main/employe_leave%20request.jpg?raw=true"/>
    -----
## Database Schema
The system uses the following database tables:
- User: Stores employee information
- LeaveType: Defines different types of leave
- LeaveRequest: Tracks all leave requests
- LeaveBalance: Maintains leave balances for employees
---
## License
This project is licensed under the MIT License. See the LICENSE file for details.
---
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
---
## Contact
