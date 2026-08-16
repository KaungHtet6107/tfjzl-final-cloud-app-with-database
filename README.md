# Online Course Application with Exam Assessment

A Django-based Online Course application enhanced with an **online examination and assessment system**.

This project was developed as part of the **IBM Full Stack / Django Final Project**. The original application provides online courses, instructors, learners, lessons, enrollment, registration, and authentication. The project extends it with an examination system that allows enrolled learners to take exams, submit answers, receive an automatically calculated score, and review detailed exam results.

---

## Project Overview

The application allows users to:

- Register for an account
- Log in and log out
- View available courses
- View course details and lessons
- Enroll in courses
- Take course examinations
- Select multiple answers for exam questions
- Submit exam answers
- Automatically calculate exam scores
- View pass/fail results
- Review correct and incorrect answers
- Retake an exam after failing

Administrators can use the Django Admin Site to create and manage:

- Instructors
- Learners
- Courses
- Lessons
- Questions
- Choices
- Exam submissions

---

## Technologies Used

### Backend

- Python
- Django 4.2.3
- Django ORM
- SQLite

### Frontend

- HTML5
- CSS3
- Bootstrap 4.5.2
- Django Template Language

### Development Tools

- Git
- GitHub
- IBM Skills Network Cloud IDE
- Django Development Server

---

## Project Structure

```text
tfjzl-final-cloud-app-with-database/
│
├── manage.py
│
├── myproject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── onlinecourse/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── migrations/
│
├── templates/
│   └── onlinecourse/
│       ├── course_list_bootstrap.html
│       ├── course_detail_bootstrap.html
│       ├── exam_result_bootstrap.html
│       ├── user_login_bootstrap.html
│       └── user_registration_bootstrap.html
│
├── media/
│   └── course_images/
│
├── db.sqlite3
│
└── README.md

**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)


Create an admin user
Let's create an admin user with the following details:

Username: admin
Email address: leave blank by pressing enter
Password: Your choice, or use p@ssword123
