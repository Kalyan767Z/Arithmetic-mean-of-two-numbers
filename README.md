
# Arithmetic Mean of Two Numbers Program

## Instructions for Running the Program

1. Open **Visual Studio** or any C# IDE of your choice.
2. Copy and paste the code from the provided source file into the IDE.
3. Compile and run the program.
4. Follow the on-screen instructions to input the numbers and see the results.

## Tasks Performed by the Program

- The program calculates the arithmetic mean of two user-provided numbers.
- Input validation is performed to ensure only valid integers or doubles are accepted.
- The program provides clear error messages for invalid inputs.
- Modularized design with clear separation of logic into reusable methods.

## Description of the Program

This program calculates the arithmetic mean (average) of two numbers. Users input two numbers, and the program ensures the values are valid. The calculation is then performed using a straightforward mathematical formula, and the result is displayed.

### Key Aspects:

- **Validation**: Uses `double.TryParse` to ensure input correctness.
- **Error Handling**: Handles invalid inputs gracefully with informative messages.
- **Structure**: Implements modular functions to make the program more maintainable and readable.

## Features of the Program

### Step-by-Step Explanation:

1. The user is prompted to enter two numbers.
2. Each input is validated using `double.TryParse` to ensure it can be processed as a numeric value.
3. If either input is invalid, the program provides an appropriate error message and terminates.
4. If both inputs are valid, the arithmetic mean is calculated using the formula:  
5. The calculated mean is displayed as the output.

### Functions Overview:

- **`InputAndValidateNumber(string prompt)`**:
  - Displays a prompt for the user to enter a number.
  - Validates the input using `double.TryParse` and returns the value if valid.
  - Handles invalid input by displaying an error message and exiting the program.

- **`CalculateArithmeticMean(double num1, double num2)`**:
  - Takes two numbers as input.
  - Returns the arithmetic mean using the formula.

- **`Main()`**:
  - Coordinates the flow of the program.
  - Calls the input function twice to get two numbers.
  - Invokes the calculation function and displays the result.

## Program Logic Summary

The program provides an easy-to-follow workflow for calculating an average while ensuring robust error handling. It focuses on clarity and reusability, making it suitable for both beginners and professional programmers interested in clean C# code.

