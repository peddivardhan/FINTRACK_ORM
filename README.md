# FinTech ORM - Personal Finance Tracker

A CLI-based Personal Finance Tracker built using Python and SQLAlchemy ORM.  
This project helps users manage expenses, categories, budgets, and subscriptions using a structured SQLite database.

---

# Project Description

This application allows users to:

- Create and manage expense categories
- Add, update, and delete transactions
- Search transactions by date
- View total spending by category
- Set monthly budgets
- Get alerts when budget limits are exceeded
- Manage subscriptions

The project uses SQLAlchemy ORM to handle database operations efficiently.

---

# Technologies Used

- Python
- SQLAlchemy (ORM)
- SQLite
- Command Line Interface (CLI)

---

# Database Tables

# 1. Categories
Stores expense categories such as Food, Travel, Shopping, etc.

# 2. Transactions
Stores:
- Amount
- Description
- Date
- Category reference (Foreign Key)

# 3. Budgets
Stores monthly budget limits for each category.

# 4. Subscriptions
Stores:
- Subscription name
- Amount
- Start date
- End date

---

# How It Works

1. The user runs the program.
2. A menu is displayed with multiple options.
3. Based on user selection:
   - Data is taken as input
   - SQLAlchemy maps the data to database tables
   - Changes are committed to the SQLite database
4. The system can calculate total spending per category and compare it with the monthly budget to generate alerts.

