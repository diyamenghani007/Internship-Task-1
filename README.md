# Internship-Task-1
Student Management System Database
This project contains the schema for a Student Management System, designed to manage students, courses, instructors, and departments.

Project Structure
ER Diagram: Visual representation of entities and relationships.
Schema Script: SQL script to create the database and tables.

Tools Used
- MySQL Workbench

Schema Overview
The database schema includes the following entities:
1. Students
   - Attributes: 'StudentID', 'FirstName','LastName', 'Email', 'DateOfBirth', 'DepartmentID'
2. Courses
   - Attributes: 'CourseID', 'CourseName', 'Credits', 'InstructorID', 'DepartmentID'
3. Enrollments
   - Attributes: 'EnrollmentID', 'StudentID', 'CourseID', 'EnrollmentDate', 'Grade'
4. Instructors
   - Attributes: 'InstructorID', 'Name', 'Email', 'DepartmentID'
5. Departments
   - Attributes: 'DepartmentID', 'DepartmentName'
