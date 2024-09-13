[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/8irlYfOA)

## School Database System
A comprehensive database system designed to manage students, faculty, and course information. This system allows administrators, faculty, and students to interact with the database efficiently. Built using SQL and designed for role-based access, it ensures data integrity and streamlined management of school operations.

## Requirements:
MySQL Server (local or remote)
SQL Script for database structure
Any SQL client to run the provided scripts

## Features
Manage Student and Faculty Records: Add, update, and delete student, professor, and administrator details.
Course Management: Register students for courses while checking prerequisites and preventing scheduling conflicts.
Role-Based Access Control: Limit functionality based on user roles, such as professors managing grades and administrators overseeing schedules.
Student Lifecycle Management: Manage user transitions from applicants to students, and then alumni, ensuring continuity in access and data management.
Support Chat: Provide students with a support chat feature for course and school-related inquiries.

## Usage
Dashboard: Access student, faculty, and course management options through the system interface.
Add New Records: Use SQL queries or forms to add students, faculty, and schedule courses.
Manage Records: View and update existing records, including course registration and scheduling details.
Support: Chat system available for students to ask questions regarding their courses and other inquiries.

## Installation
1. Clone the repository from GitHub:

```bash
git clone https://github.com/mazenesaadi/School-Database-System-Project.git
```

2. Navigate to the cloned directory:

```bash
cd school-database-management
```

3. Install the necessary Python packages:

```bash
pip install -r requirements.txt
```

4. Import the MySQL database structure and initial data from `dataManage.sql` into your MySQL server. You can do this by accessing your MySQL Command-Line Client and executing:

```sql
source path/to/dataManage.sql;
```

## Configurations
Before using the system, configure your database connection settings. Update the MySQL server details in your configuration file (if applicable):

```python
USER = 'your_mysql_username'
PASSWORD = 'your_mysql_password'
DB = 'your_database_name'
HOST = 'your_host'
```
Replace 'your_mysql_username', 'your_mysql_password', 'your_database_name', and 'your_host' with your actual MySQL credentials.

## Running the System
Once installation and configuration are complete, you can run the application by connecting to the database through your preferred SQL client. Use the provided queries and scripts to manage student, faculty, and course data.

```bash
flask run
```

By default, the flask app will run on http://127.0.0.1:5000/. 

## Contact
If you would like to reach out to me, you can do so at mazenesaadi@gwu.edu



