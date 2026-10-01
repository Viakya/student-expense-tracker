# Overview
Student Expense Tracker is a simple, responsive web app built with HTML, CSS, and vanilla JavaScript. It lets students quickly add expenses with description, category, amount, and date; see total spending; visualize spending by category; and manage expenses in a clean dashboard. All data is saved locally in the browser using localStorage—no server required.

Key features:
- Add and delete expenses
- Dynamic total spending and transaction count
- Visual spending breakdown by category with color-coded bars and legend
- Search and category filter for the expense table
- Fully responsive, modern UI
- Data persistence via localStorage

# Setup
No build tools are required.

1. Download the repository or copy the files.
2. Open index.html in any modern browser.

Everything runs locally.

# Usage
- Add an expense:
  - Enter a description (e.g., “Textbook”, “Coffee”).
  - Choose a category.
  - Enter the amount (number > 0).
  - Pick a date (defaults to today).
  - Click “Add Expense”.

- View dashboard:
  - Total Spending shows the sum of all visible expenses.
  - Top Category highlights where you spend the most.
  - Spending by Category shows a proportional bar for each category and a legend.

- Manage expenses:
  - Use the search box to filter by description.
  - Use the category filter to narrow by category.
  - Click “Delete” in a row to remove that expense.
  - Click “Clear All” to remove all expenses (with confirmation).

- Data:
  - Expenses are saved automatically to localStorage and persist across page reloads.
  - Currency is formatted to your browser’s locale when possible.