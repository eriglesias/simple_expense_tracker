# Expense Tracker - Simple OOP Demo

This is a dummy program created to demonstrate an extremely simple implementation of Object-Oriented Programming (OOP) in Python. The program simulates an expense tracker that allows users to add, remove, view, and calculate total expenses.

## Classes

### `Expense`
Represents a single expense with the following attributes:
- `date`: The date of the expense.
- `description`: A brief description of the expense.
- `amount`: The amount of the expense.

### `ExpenseTracker`
Manages a list of expenses and provides methods to interact with them:
- `add_expense(expense)`: Adds an `Expense` object to the list.
- `remove_expense(index)`: Removes an expense from the list by its index.
- `view_expenses()`: Displays all expenses.
- `total_expenses()`: Calculates and displays the total amount of all expenses.

## Main Program

The main program provides a simple command-line interface for the user to interact with the expense tracker. The user can:
1. Add a new expense.
2. Remove an existing expense by its index.
3. View all added expenses.
4. View the total amount of all expenses.
5. Exit the program.

## Usage

1. Run the program.
2. Follow the menu prompts to add, remove, view, and total expenses.
3. Exit the program by selecting option 5.

```python
# To run the program, save the code in a file (e.g., expense_tracker.py) and execute it with Python:

python expense_tracker.py
