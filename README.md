# calculator-documentation
Documentation on analysis of a simple calculator project.
Link to project: https://gist.github.com/dan49075/b26ca718937635e2f7a7

Introduction
This project is a simple calculator implemented in C. It performs basic arithmetic operations: addition, subtraction, multiplication, and division. The user selects an operation from a menu and then inputs the numbers to be operated on. The program then displays the result.

Program Structure
The program consists of a single main function, which handles user interaction, input, calculation, and output.

Analysis:

Menu Display:
The program starts by displaying a menu with four options for the user to choose from: Addition, Subtraction, Multiplication, and Division. The user is prompted to enter a number corresponding to the desired operation.

Switch Statement and Operations:
After the user inputs a number, a switch statement processes the user's menu choice. Depending on the user's input (1-4), the program will perform the corresponding arithmetic operation.

For each case (1-4), the program prompts the user to enter two numbers. It then performs the calculation based on the selected operation and stores the result in the result variable.

If the user enters a number outside the range 1-4, the program outputs an error message.

Result and Error Handling
For each arithmetic operation, the program prints the result in a readable format. If the user enters an invalid option, the program prompts them to enter a correct number.
