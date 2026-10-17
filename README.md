# Student Portal

A command-line student grade system written in Python. After logging in, users can add a grade for an existing student, remove a student, view a grade average, or list the students.

## Requirements

- Python 3

The program uses only Python's standard library; no additional packages are required.

## Run

From the project directory, run:

```bash
python3 StudentPortal.py
```

Enter a username and password configured in the `admins` dictionary in `StudentPortal.py`. After a successful login, select an action from the menu:

1. Add a grade to an existing student
2. Remove a student
3. View the grade average for the last student in the student list
4. List all students
5. Exit

Student names and grades are defined in `studentDict` in `StudentPortal.py`. Changes made while the program is running are kept in memory and are not saved between runs.

## Author

Navneet Tyagi
