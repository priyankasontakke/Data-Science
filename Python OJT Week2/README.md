# Student Grade Calculator

**Python Internship - Week 2: Making Decisions & Repeating Tasks in Python**

## 1. Project Overview

The Student Grade Calculator is a Python-based project that accepts a student's name and marks, calculates the grade, and displays an encouraging message.

This project demonstrates basic Python programming concepts such as conditional statements, loops, functions, input validation, and error handling.

## 2. Project Objectives

- To understand if-elif-else statements.
- To use comparison operators.
- To create and use functions.
- To implement while loops.
- To validate user input.
- To handle invalid input using try-except.
- To display grades with encouraging messages.

## 3. Technologies Used

- Programming Language: Python
- Code Editor: Visual Studio Code
- Execution Environment: Windows Command Prompt / Terminal

## 4. Grading System

| Marks | Grade | Message |
|---|---|---|
| 90-100 | A | Excellent work! Keep shining! |
| 80-89 | B | Very Good! Keep it up! |
| 70-79 | C | Good effort! Keep practising! |
| 60-69 | D | You passed! Work hard to improve! |
| 0-59 | F | Don't give up. Learn and try again! |

Marks below 0 or above 100 are rejected by the program.

## 5. Project Structure

```text
Python_Week2_Grade_Calculator/
|
|-- grade_calculator.py
|-- README.md
|-- test_cases.txt
|
|-- screenshots/
    |-- valid_result.png
    |-- invalid_range.png
    |-- invalid_text.png
```

## 6. Installation and Setup

### Requirements
- Python 3 installed on the computer.
- Visual Studio Code or another code editor.

### Steps to Run the Program

1. Install Python from https://www.python.org/downloads/
2. Open the project folder in Visual Studio Code.
3. Select Terminal -> New Terminal.
4. Run this command:

```bash
python grade_calculator.py
```

5. Enter the student's name.
6. Enter marks between 0 and 100.
7. View the grade and encouraging message.

If the `python` command does not work on Windows, try:

```bash
py grade_calculator.py
```

## 7. Functions Used

### get_grade(marks)
This function uses if-elif-else statements to determine the grade and return an encouraging message.

### get_valid_marks()
This function uses a while loop to repeatedly ask for marks until valid numeric marks between 0 and 100 are entered.

### main()
This function accepts the student's name, calls the other functions, and displays the final result.

### Error Handling
The try-except statement handles non-numeric input and prevents the program from crashing because of invalid marks input.

## 8. Algorithm

1. Start the program.
2. Enter the student's name.
3. Check that the name is not empty.
4. Enter marks.
5. Validate that the marks are numeric and within 0-100.
6. Ask again if the input is invalid.
7. Calculate the grade using conditional statements.
8. Display the student's name, marks, grade, and message.
9. End the program.

## 9. Sample Output

```text
STUDENT GRADE CALCULATOR

Enter student name: Priyanka
Enter marks (0-100): 95

RESULT FOR PRIYANKA
Marks: 95/100
Grade: A
Message: Excellent work! Keep shining!

Thank you for using Student Grade Calculator!
```

## 10. Testing

The program was tested with the following inputs:

- Marks 95: Grade A displayed successfully.
- Marks 120: Invalid marks message displayed.
- Marks abc: Invalid input message displayed.

Additional test cases for other grades, negative marks, boundary values, and decimal marks are documented in `test_cases.txt`.

## 11. Screenshots

The `screenshots` folder contains screenshots demonstrating:

1. Successful grade calculation.
2. Validation for marks above 100.
3. Validation for non-numeric input.

These screenshots provide evidence of the program's execution and input validation.

## 12. Conclusion

The Student Grade Calculator demonstrates the use of conditional statements, functions, loops, and exception handling in Python. It validates input, assigns grades according to the specified grading system, and provides encouraging feedback to students.

This project helped improve my understanding of Python programming fundamentals.

## 13. Author

**Python Internship Student**

Project: Student Grade Calculator  
Week: 2