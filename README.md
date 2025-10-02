# Course Management System with Quiz

A Python-based educational system that manages user registration, 
course enrollment, and quizzes with persistent JSON storage.

## Features

### User Management
- Register with:
  - Unique username
  - Valid and unique email
  - Strong password (a–z, A–Z, 0–9, min length 6)
  - Age between 18–50
  - Two security questions
- Login with password
- Password reset via security questions
- Auto-generated unique User IDs

### Course Management
- View available courses with capacity
- Enroll in courses with a valid start date
- Prevent duplicate enrollments
- Capacity control for each course

### Quiz System
- Each course can have a quiz
- Multiple-choice questions
- Score calculation and Pass/Fail (40% threshold)
- Results stored in user profile

### Storage
- Users stored in `users_json.json`
- Courses stored in `courses.json`
- Quizzes stored in `quiz.json`

## How to Run
--- Main Menu ---
1. Register
2. Login
3. Exit
Choose : 1
Enter username : arad
Enter Email : arad@mail.com
Enter Password : Test123
Enter birth year (e.g. 2001): 2000
Who is the creator of Python language? Guido
Which keyword defines a function in Python? def
Registration successful!

--- Main Menu ---
1. Register
2. Login
3. Exit
Choose : 2
Enter username : arad
Enter password (or type 'forgot'): Test123
Login successful!

```bash
python course_system.py
