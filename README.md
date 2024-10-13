Name: SIVAMAALINI
Company: CODETECH IT SOLUTIONS
ID: CT08DS9103
Domain: C PROGRAMMING
Duration: October 10th,2024 to November 10th,2024
Mentor: Neela Santhosh Kumar

OVERVIEW of the Project:
Project:  Student Management System
  The student management system is a simple C program designed to handle basic student registrations and display student information. It allows users to add student records and display the list of registered students, including their names and grades.

Key Features:
Data Structure:

The program defines a Student structure that holds:
  -An integer id to uniquely identify each student.
  -A character array name to store the student's name.
  -An array of floats grades to hold five grades for each student.
Constants:

MAX_STUDENTS: The maximum number of students that can be registered (set to 10).
NAME_LENGTH: The maximum length of the student’s name (set to 50).
Global Variables:

  -An array students of type Student to store the registered student records.
  -An integer student_count to track the current number of registered students.
Functions:
add_student:

  -Checks if the maximum student limit has been reached.
  -Prompts the user to enter a student's name and five grades.
  -Assigns a unique ID to the new student and stores the information in the students array.
display_students:

  Iterates through the registered students and prints their ID, name, and grades in a formatted manner.
main:

Contains a loop that presents a menu to the user:
  -Option to add a student.
  -Option to display all students.
  -Option to exit the program.
  -Calls the corresponding functions based on user input.
Example Workflow:
  -The program starts and displays a menu with options.
  -The user selects an option:
  -To add a student: The program prompts for the student's name and grades, then confirms that the student has been added.
  -To display students: The program lists all registered students with their IDs, names, and grades.
  -To exit: The program terminates.
Error Handling:
  -The program checks if the maximum number of students has been reached before adding a new student.
  -It handles invalid menu selections by informing the user.
Conclusion
  This student management system is a straightforward implementation that demonstrates essential programming concepts, including structure definitions, array handling, user input, and basic control flow. It provides a foundational framework that can be expanded with additional features, such as editing or deleting student records, calculating averages, or persisting data.



