# Personal Expense Tracker (Python CLI + GUI)

A simple Personal Expense Tracker built with Python, supporting both Command Line Interface (CLI) and Graphical User Interface (GUI) using Tkinter.
This project helps you manage daily expenses by allowing you to add, view, and delete expenses. Data is stored in a CSV file for persistence.

## Features

* Add Expense with category, description, and amount
* View Expenses in tabular format (CLI) or table (GUI)
* Delete Expense by ID or row selection
* CSV File Storage (no external database required)
* Dual Mode – Run in CLI or Tkinter GUI

## Project Structure
├── expense_tracker.py     # Main project file/n
├── expenses.csv           # Data file (auto-created on first run)/n
└── README.md              # Project documentation/n

## Requirements

* Python 3.x
* Tkinter (pre-installed with Python)
* No external libraries required

## How to Run
1. Clone the Repository
git clone https://github.com/your-username/expense-tracker.git
cd expense-tracker

2. Run the Program
python expense_tracker.py

3. Choose Mode

When you start the program, you will be asked:
Choose mode:
1. CLI
2. GUI


Enter 1 for Command Line Interface
Enter 2 for Graphical Interface (Tkinter)

## Usage
🔹 Add Expense
Enter category, description, amount
Date and ID are auto-generated

🔹 View Expenses
CLI: Expenses shown in table format
GUI: Expenses shown in a sortable Tkinter table

🔹 Delete Expense
CLI: Enter the ID of expense to delete
GUI: Select a row and click Delete Selected

## Data Storage
All data is stored in expenses.csv file in the following format:
ID, Date, Category, Description, Amount
1, 2025-09-09 13:45:23, Food, Lunch at cafe, 250
2, 2025-09-09 15:20:11, Travel, Bus ticket, 40

## Future Improvements
Add monthly/weekly expense summary
Support expense categories with charts
Export data to Excel or PDF
Add search & filter features in GUI
