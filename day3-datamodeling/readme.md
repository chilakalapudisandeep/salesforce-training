APP :
A collection of related components (objects, tabs, dashboards)
Used to perform a specific business function
Example: Sales App
OBJECT :
A database table that stores data
Example: Student, Course
RECORD :
A single entry (row) in an object
Example: One student’s details
FIELD :
A column in an object that stores specific information
Example: Name, Age, Email

STANDARD vs CUSTOM OBJECTS :
Standard Objects :
Pre-built by Salesforce
Common business usage
Example: Account, Contact
Custom Objects :
Created by users based on requirements
Example: Student, Faculty

COLLEGE DATA MODEL :

Objects Created:
Student
Faculty
Course
Department

RELATIONSHIPS :
Department → Course (One-to-Many)
👉 One department has many courses
Course → Student (One-to-Many)
👉 One course has many students
Faculty → Course (Lookup)
👉 One faculty teaches a course
Student → Department (Lookup)
👉 Student belongs to a department

STRUCTURE :
Department
   ↓
Course
   ↓
Student
Faculty → Course
Student → Department

VALIDATION RULES :
1. Email Cannot Be Empty
Prevents:
Missing important contact info
2. Student Age Cannot Be Negative
Prevents:
Invalid or incorrect data entry
3. Course Seats Limit
Rule:
Enrolled students ≤ Total seats
Prevents:
Overbooking of courses

Why Structured Data Matters:
Companies need structured data because:
Data is organized and easy to manage
Faster searching and reporting
Avoids duplication and inconsistency
Supports automation and workflows
Improves decision-making
Random spreadsheets:
Cause errors
Hard to maintain
No relationships between data
<img width="1407" height="809" alt="Screenshot 2026-05-11 at 5 08 57 PM" src="https://github.com/user-attachments/assets/817fc0cb-ff0c-49b4-bdaa-2924357bd27e" />
<img width="1440" height="900" alt="Screenshot 2026-05-07 at 9 07 08 PM" src="https://github.com/user-attachments/assets/d24221e3-23d4-46ef-b60c-a9f7345d3bb7" />

