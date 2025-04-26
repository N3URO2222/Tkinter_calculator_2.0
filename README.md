Calculator Application Using Tkinter
Overview
This project is a simple GUI-based calculator application built using Python's tkinter module. The application allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division. The design focuses on user-friendly interface and input validation for reliable calculations.

Features
Numeric Input: Buttons for numbers 0-9 for easy data entry.

Operators: Support for addition (+), subtraction (-), multiplication (*), and division (/).

Input Display: An entry field (Entry) for showing current inputs and calculation results.

Error Handling:

Validates inputs to ensure proper calculations.

Prevents division by zero and displays an error message if attempted.

Clear Functionality: A dedicated button to reset the input field.

Chained Calculations: Allows users to continue calculations with the result of a previous operation.

How to Use
Open the application window.

Enter numbers using the numeric buttons.

Choose an arithmetic operator (+, -, *, /).

Input the next number and press = to compute the result.

Use the Clear button to reset the input field if needed.

Code Highlights
Functionality:

click(num): Appends the clicked button's number to the input field.

Individual functions (add(), sub(), mult(), div()) to handle arithmetic operations, storing the first number and operator type.

equal(): Computes the result of the operation, handles errors, and updates the input field.

clear(): Resets the input field.

Error Handling: Implements exception handling for invalid inputs and division by zero.

Requirements
Python 3.x installed on your system.

The tkinter module (pre-installed with Python).
