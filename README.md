# Simple-Calculator
## Simple Calculator
This project is a basic calculator that performs arithmetic operations based on user input. The user can input two numbers and choose an operation, and the calculator will display the result.

## How It Works
The program prompts the user to enter two numbers.
The user selects an operation from the following options:
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
The calculator performs the operation and displays the result.

## Input Requirements
**Two numbers:** The user enters two numeric values (integers or decimals).
**Operation choice:** The user selects one of the following operations: +, -, *, or /.
**Error handling:** If the user enters an invalid operation, the program prompts them to try again.

## Output
Displays the result of the calculation with a message showing the selected operation and numbers.

## Code Explanation
### Function Definition (calculator()):
The entire logic of the calculator is placed inside a function named calculator().
### User Input:

The user is prompted to enter two numbers. These are converted to float to allow decimal calculations.
The user is also prompted to choose an arithmetic operation (+, -, *, /).
###### Arithmetic Operations:

The program checks the user's choice and performs the corresponding operation:
**Addition (+):** Adds the two numbers.
**Subtraction (-):** Subtracts the second number from the first.
**Multiplication (*):** Multiplies the two numbers.
**Division (/)**: Divides the first number by the second. If the second number is 0, it prints an error message instead.

### Error Handling:

If the user inputs an invalid operation, the program prints an error message and exits the function.
If division by zero is attempted, the program prints a specific error message and stops further execution.
### Display Result:

If the operation is valid, the result is printed in a formatted string showing both the operation and the numbers used.
### Function Call:

The function calculator() is called to start the program.



