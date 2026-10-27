Student Registration System
A simple Python command-line application for managing student records and course registrations.
Features
- Add a student using a student ID and name.
- Register a student for a course.
- Display all students and their registered courses.
- Exit the program through an interactive menu.
- Includes a class method that loads fictional sample student records.
Requirements
- Python 3.8 or newer
- No third-party packages are required for the code shown in the screenshots.
How to Run
1. Save your Python program in a file, for example student_registration.py.
2. Open a terminal in the folder containing the file.
3. Run:
   python student_registration.py
   On some systems, use python3 student_registration.py.
4. Follow the menu and enter an option from 1 to 4.
Menu Options
Option	Action
1	Add a student
2	Register a student for a course
3	Display all students
4	Exit the program


Screenshots
1. Registration system code

2. Command-line menu

3. Course registration method

4. Menu handling code

Sample Student Records
The sample-data method shown in the code creates these fictional records:
- ST001 — Aminata Kamara — OOP 1
- ST002 — Joseph Conteh — Database Systems
Notes
- Student records are held in memory while the program runs. They will not persist after the program exits unless file or database storage is added.
- A student ID should be unique.
- A course name should not be empty, and duplicate course registrations should be rejected.
Possible Improvements
- Save and load student records from a JSON file or database.
- Add input validation and clearer error messages.
- Add automated tests for student creation and course registration.
