# Programming in Python

This is a mini project I created when I returned back to studies to refresh knowledge in Python.  Here, the problem statement was to create a small 
application that would compute the area of common geometric shapes such as square, rectangle, triangle, and circle. This program is a menu-driven written in Python.
It validates user input, ensures only numeric values are accepted, and provides clear error messages for invalid selections.

The objective is to explore my technical skills in Python to come up with a solution.

## Tools:
- Anaconda (Python Notebook)

## Key Features
- Interactive Menu: Users select a shape by entering a number (1–4).
- Input Validation: Ensures only valid numeric inputs are processed.
- Reusable Helper Function: get_number() centralizes numeric input handling.
- Error Handling: Invalid selections or inputs terminate gracefully with clear feedback.
- Modular Design: Each shape has its own function for clarity and reusability.

## Program Flow
- Display menu with shape options.
- User selects a shape (1–4).
- Validate selection:
- If invalid → terminate program.
- If valid → proceed to shape function.
- Prompt user for required dimensions.
- Validate inputs (must be numeric).
- Compute and display area.
- End program.

Solution:

- Defined main() function, Displays menu, validates selection, and calls the appropriate shape function
- Created User Define Functions for the following:
    a. Numeric Input
    b. Area Calculations
    c. Validation

This simple program covers python's:
- Conditional statement (if)
- error handling
- PEP8 naming conventions

Disclamer:  The UDF may not always be required since this program is really small but to make the coding more efficient and practice coding standards, I decided to add them anyways.  There are various ways to code this but I decided to add this one in particular for my own personal thing.

