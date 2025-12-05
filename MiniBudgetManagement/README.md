# Programming in Python

This is a mini project I created when I returned back to studies to refresh knowledge in Python.  Here, the problem statement was to create a small finance tracker application that would keep track of the finance expenses and budget while the program is running. This program is a menu-driven budget tracker written in Python.
## It allows users to:
- Add or subtract expenses
- Add or remove income
- Continuously check remaining budget and total expenses
- Exit gracefully with a final budget summar

The objective is to explore my technical skills in Python to come up with a solution.

## Tools:
- Anaconda (Python Notebook)

## Key Features
- Interactive Menu: Users select options via numeric input.
- Expense Tracking: Expenses are added or subtracted, updating both budget and expense totals.
- Income Management: Income can be added or removed from the budget.
- Budget Check: After each operation, the program reports the remaining budget and total expenses.
- Error Handling: Invalid inputs are caught and prompt the user to retry.

## Program Flow
1. 	Start with an initial budget of 5000 and 0 expenses.
2. 	Display menu options:
 	 → Add Expenses
 	 → Subtract Expenses
 	 → Add Income
 	 → Remove Income
 	 → Exit
3. 	Perform the selected operation.
4. 	Show updated budget and expenses.
5. 	Repeat until the user chooses Exit (5)

Solution:

- Defined main() function, within the function I declared variables (menu, budget, and expense)
- Used while loop to control the program flow
- Created User Define Functions for the following:
    a. Add Expense
    b. Subtract Expense
    c. Add Budget
    d. Substract Budget
    e. Validation

This simple program covers python's:
- tuple
- loop
- error handling
- PEP8 naming conventions
- simplified arithmetic

Disclamer:  The UDF may not always be required since this program is really small but to make the coding more efficient and practice coding standards, I decided to add them anyways.  There are various ways to code this but I decided to add this one in particular for my own personal thing.
