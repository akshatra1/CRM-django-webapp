
# Django CRM Project

This is a Django-based CRM (Customer Relationship Management) web application with features such as user authentication, customer record management, and admin-specific privileges.


## Table of Contents

 - Project Overview
 - Features
 - Requirements
 - Installation

## Project Overview
This Django CRM project is designed to help businesses manage customer data efficiently. It includes user registration and authentication, allowing users to log in as admin or regular users. Admin users have special privileges to manage customer records.

## Features
- User Registration: Users can create new accounts with a username and password.
- User Authentication: Users must log in to access the CRM functionalities.
- Admin Privileges: Admin users can perform CRUD (Create, Read, Update, Delete) operations on customer records.
- Customer Record Management: Users can add, update, and delete customer records.
- User Access Control: Only authenticated admin users can access customer data.

## Requirements
To run this project, you need the following installed on your system:


Any modern web browser
Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/django-crm-project.git
```
Navigate to the project directory:
```bash
cd django-crm-project
Create a virtual environment (optional but recommended):
```
```bash
Copy code
python -m venv venv
Activate the virtual environment:
```
On Windows:

```bash
venv\Scripts\activate
```

```bash
source venv/bin/activate
```

Install project dependencies:
```bash
pip install -r requirements.txt
```
Run database migrations:

```bash
python manage.py migrations
python manage.py migrate
```

```bash
Create a superuser (admin account):
```


```bash
python manage.py createsuperuser
```

Start the development server:

```bash
python manage.py runserver
```

## Open your web browser and access the application at http://127.0.0.1:8000/.

# Usage
Open your web browser and navigate to http://127.0.0.1:8000/.
Register a new user account or log in with the admin account created during installation.
Once logged in, you can access the CRM functionalities:
Admin Dashboard: Only accessible to admin users, where you can manage customer records.
Customer Records: View, add, update, and delete customer records.
Log out when you are done.
# Contributing
If you'd like to contribute to this project, please follow these steps:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test thoroughly.
- Create a pull request with a clear description of your changes.

## Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and test thoroughly.
Create a pull request with a clear description of your changes.
