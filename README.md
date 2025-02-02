﻿# Event_Management_App
Overview
The Event Management System is a web-based application designed to help users discover, manage, and register for events seamlessly. It includes features such as user authentication, event creation, editing, deletion, registration management, and admin capabilities for user promotion and event oversight.

Features:
User Authentication : Users can register, log in, and log out.
Event Management : Admins and organizers can create, edit, delete, and view events.
Event Registration : Users can register for events, and registration status is tracked.
Admin Panel : Admins can promote users to admin roles and manage users.
Export Attendees : Admins can export a list of attendees for an event.
Pagination & Sorting : Events can be paginated and sorted by date, title, or location.


Installation:
Prerequisites
PHP 7.4 or higher
MySQL or MariaDB

Steps:
Clone the Repository:
git clone https://github.com/your-repo/event-management.git
cd event-management

Database Configuration:


Project Structure:
event-management/
├── database.sql
├── .htaccess
├── index.php
├── logout.php
├── README.md
├── api/
│   ├── attendees.php
│   ├── events.php
│   ├── reports.php
│   └── search.php
├── assets/
│   ├── css/
│   │   └── custom.css
│   └── js/
│       └── main.js
├── config/
│   ├── config.php
│   └── database.php
├── includes/
│   ├── auth.php
│   ├── event.php
│   └── registration.php
├── templates/
│   ├── footer.php
│   ├── header.php
│   └── navigation.php
└── views/
    ├── event-delete.php
    ├── event-details.php
    ├── event-edit.php
    ├── events-list.php
    ├── export-attendees.php
    ├── login.php
    ├── register.php
    ├── set-admin.php
    └── user-management.php


Usage:
Register a New User:
Navigate to /views/register.php.
Fill out the form with your name, email, and password.

Log In:
Navigate to /views/login.php.
Use your registered credentials to log in.

Create an Event:
After logging in, go to the dashboard (/views/dashboard.php).
Click "Create New Event" and fill out the form.

Manage Events:
From the dashboard, you can edit, delete, or export attendee lists for events.

Promote Users to Admin:
Admins can promote users to admin roles from the "User Management" section (/views/user-management.php).

Register for Events:
Users can view event details and register for events via /views/event-details.php.

Fork the repository:
Create a new branch (git checkout -b feature/YourFeatureName).
Commit your changes (git commit -m "Add YourFeatureName").
Push to the branch (git push origin feature/YourFeatureName).
Open a pull request.


License:
This project is licensed under the MIT License. See the LICENSE file for details.

