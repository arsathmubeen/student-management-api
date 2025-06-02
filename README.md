# Student Management System - Backend API

## Features
- Add, view, update, and delete student records via REST API
- Built using Python Flask and SQLite3

## API Endpoints

| Method | Endpoint           | Description              |
|--------|--------------------|--------------------------|
| GET    | /students          | Get all students         |
| GET    | /students/<id>     | Get single student       |
| POST   | /students          | Add new student          |
| PUT    | /students/<id>     | Update student           |
| DELETE | /students/<id>     | Delete student           |

## How to Run
```bash
pip install -r requirements.txt
python app.py
