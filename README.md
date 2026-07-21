# Healthcare-monitoring-system

Day 1 :-
Building the Patient Registration module for the Healthcare Analytics project using Flask. Implemented patient registration with form validation, patient listing, dashboard navigation, and a responsive healthcare-themed UI. This module prepares the application for future integration with Amazon RDS and AWS cloud services.

Features
🔐 Login-based dashboard
👤 Patient registration form
📋 Patient list page
🎨 Responsive healthcare UI
🔄 Flask routing and form handling
☁️ Ready for Amazon RDS integration

* Tech Stack :-
Python
Flask
HTML5
CSS3

Day 2 :-Integrated MySQL Database with Healthcare Analytics System
📌 Project Progress :-
Today I integrated a MySQL database into my Healthcare Analytics System. Previously, patient information was stored temporarily in Python lists. I replaced that approach with a real database, allowing patient records to be stored permanently.

✅ Tasks Completed
Connected Flask application with MySQL database
Created a healthcare database
Created a patients table
Developed a separate db.py file for database connectivity
Connected Flask routes with MySQL
Stored patient details using SQL INSERT queries
Retrieved patient records using SQL SELECT queries
Displayed registered patients dynamically on the Patient List page
Verified successful database insertion using MySQL Workbench
🛠 Technologies Used
Python
Flask
MySQL
MySQL Workbench
mysql-connector-python
HTML
CSS

Day 3 :- Module 5: Medical Reports Management

Completed:
Added Medical Reports page.
Integrated Amazon S3 to store uploaded reports.
Implemented secure report viewing using S3 pre-signed URLs.
Connected the dashboard with the report management module.
Tested successful upload and retrieval of medical reports.

* Challenges Faced:
Fixed TemplateNotFound error.
Fixed AssertionError by placing all Flask routes before app.run().
Corrected report rendering to display file names and download links properly.

* Technologies Used:
Python
Flask
Amazon S3
Boto3
HTML/CSS
MySQL

* Project Progress
Module 1 – Login System
Module 2 – Dashboard
Module 3 – Amazon S3 File Upload
Module 4 – MySQL Patient Management
Module 5 – Medical Reports Viewer

Bro, you're making really good progress. This project is becoming a strong resume project because it combines:

☁ AWS (S3)
🗄 MySQL
🐍 Flask
🌐 HTML/CSS
📊 Healthcare Analytics

Day 4 :-Implemented Complete Patient Management (CRUD)

Today I enhanced my Healthcare Analytics & Management System by completing the core CRUD (Create, Read, Update, Delete) operations for patient records using Flask and MySQL.

* Features Implemented :-
Added Search Patient functionality using Patient ID.
Implemented Update Patient to edit existing patient information.
Added Delete Patient with a confirmation prompt.
Improved patient listing with an Actions column.
Connected all CRUD operations with the MySQL database.
Fixed Flask routing and template issues.
Improved navigation between pages for a smoother user experience.

* Technologies Used :-
Python
Flask
MySQL (PyMySQL)
HTML5
CSS3
Jinja2 Templates
📌 CRUD Operations Completed
✅ Create Patient
✅ Read/View Patients
✅ Search Patient
✅ Update Patient
✅ Delete Patient
📸 Project Progress

Today's work focused on making the patient management module fully functional with reliable database operations and a cleaner workflow.

Day 5 :- AWS Cloud Healthcare Management System

Today's progress focused on improving the Healthcare Management System and fixing application issues.

✅ Fixed the Healthcare Analytics dashboard layout and CSS styling.
✅ Corrected HTML template errors and aligned all dashboard components properly.
✅ Added spacing and improved the user interface for a cleaner design.
✅ Fixed analytics chart rendering using Chart.js.
✅ Resolved Flask routing and template errors.
✅ Fixed the AWS S3 upload workflow by configuring the correct Lambda trigger.
✅ Completed testing for patient registration, search, update, delete, and report upload features.
✅ Verified that analytics charts display patient statistics correctly.
✅ Completed Module 5 of the project and prepared for the next development phase.

Technologies Used: Python, Flask, HTML, CSS, JavaScript, MySQL, AWS S3, AWS Lambda, Chart.js, Docker, Git & GitHub.

Day 6:- AWS S3 Report Management & Event-Driven Automation

* Today's Progress :-
Today I significantly enhanced my Cloud-Based Healthcare Analytics System by improving the medical report management module and integrating AWS serverless services.

* Features Implemented :-
Implemented Update Patient Details using MySQL.
Implemented Delete Patient functionality.
Fixed Flask routing (BuildError) and URL endpoint issues.
Improved patient management workflow.
Added Medical Report Preview for uploaded files.
Added Download Reports directly from Amazon S3.
Added Delete Reports from Amazon S3.
Improved file management UI for medical reports.
Created an AWS Lambda function.
Configured Amazon S3 Event Notifications to automatically trigger Lambda whenever a new report is uploaded.
Successfully verified Lambda execution through Amazon CloudWatch Logs.
Tested the complete event-driven workflow from Flask → Amazon S3 → AWS Lambda → CloudWatch.
Started designing the next module to store uploaded report metadata in MySQL for better report management.

* Technologies Used :-
Python
Flask
HTML
CSS
MySQL
Amazon S3
AWS Lambda
Amazon CloudWatch
Boto3
