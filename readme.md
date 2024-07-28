# Student Management System

It offers various functionalities to add, view, search, update, delete, sort, and display statistics for students.

## Features

- **Insert Student Record:** Add a new student with ID, name, age, and course information.
- **View All Student Records:** Display a formatted list of all students currently in the system.
- **Search Student by ID:** Search for a specific student using their unique ID.
- **Search Student by Name:** Search for students based on their name (case-sensitive).
- **Delete Student Record:** Remove a student's record from the system after confirmation.
- **Update Student Record:** Modify the existing information of a student.
- **Sort Students by Name:** Sort the list of students alphabetically by their names.
- **Display Statistics:** Calculate and display the total number of students and their average age.

## Requirements

- C++ compiler (e.g., GCC, Clang)
- Basic understanding of C++ programming

## Installation

1. Clone this repository or download the source code.
2. Open a terminal or command prompt and navigate to the directory containing the source code (`main.cpp`).
3. Compile the code using your preferred C++ compiler (e.g., `g++ main.cpp -o student-management-system`). This creates an executable named `student-management-system`.

## Usage

1. Run the compiled executable (e.g., `./student-management-system`).
2. A menu will be displayed with various options.
3. Enter the corresponding number for the desired operation.
4. Follow the on-screen prompts to enter necessary information.

## Example Usage

1. Insert a student record:

   - Enter the student's ID (unique)
   - Enter the student's name
   - Enter the student's age (1-100)
   - Enter the student's course

2. View all student records:

   - A formatted list of all students will be displayed.

3. Search student by ID:
   - Enter the student's ID
   - The student's information will be displayed if found, otherwise a message will indicate no record found.

## Additional Notes

- The system currently allows a maximum of 100 students (adjustable by changing the `MAX_STUDENTS` constant in the code).
- Student names can be up to 50 characters long (adjustable by changing the `MAX_NAME_LENGTH` constant).
- Student course names can be up to 50 characters long (adjustable by changing the `MAX_COURSE_LENGTH` constant).
