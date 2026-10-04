# CampusConnect

CampusConnect is a web-based College Club Management System that helps students and coordinators manage and access college club and event information.

## Features

- Student Signup and Login
- Coordinator/Admin Login
- Student Dashboard
- Admin Dashboard
- Club Information
- Event Creation and Management
- View Upcoming and Past Events
- MySQL Database Integration

## Technologies Used

- HTML
- CSS
- JavaScript
- PHP
- MySQL
- XAMPP

## How to Run

### 1. Install XAMPP

Download and install XAMPP:

https://www.apachefriends.org/

### 2. Start XAMPP

Open XAMPP Control Panel and start:

```text
Apache
MySQL
```

### 3. Add the Project

Copy the project folder into the XAMPP `htdocs` folder:

```text
C:\xampp\htdocs\CC
```

### 4. Create the Database

Open phpMyAdmin:

```text
http://localhost/phpmyadmin/
```

Create a database named:

```text
college_events_db
```

Create the required tables for the project.


### 6. Run the Project

Open your browser and go to:

```text
http://localhost/CC/login.html
```

Register a new account and login to access the application.

## User Roles

### Student

Students can view clubs, upcoming events, past events and event details.

### Coordinator/Admin

Coordinators can manage clubs and create, view and update events.

## Project Workflow

```text
Signup
   ↓
Login
   ↓
Student / Coordinator Dashboard
   ↓
Club & Event Management
   ↓
Logout
```

## Database

The project uses MySQL database:

```text
college_events_db
```

The database connection is handled through:

```text
db_connect.php
```

## Note

This project is designed to run locally using XAMPP, Apache, PHP and MySQL.

---

**CampusConnect — Connect, Collaborate, Thrive**