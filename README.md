# Python-Projects
A comprehensive set of Python projects ranging from basic exercises to full applications. Perfect for students, self-learners, and anyone looking to master Python through hands-on experience.

# 🏦 Python Bank Account Management System
A simple Bank Account Management System built in Python. This program allows users to create and manage bank accounts, perform transactions (deposit, withdrawal, transfer), view transaction history, and generate summary reports.

It uses file handling with Pickle to persist account and transaction data, and includes error handling, interactive menus, and NumPy for transaction statistics.

# ✨ Features
✅ Account Management

Create new accounts (auto-generated account number)

View account details (name, account number, type, balance)

✅ Transactions

Deposit money

Withdraw money (with balance check)

Transfer money between accounts

✅ File Handling

Saves account details & transaction history using pickle

Loads saved data when program starts

Appends new transactions without overwriting previous data

✅ Reports & History

View transaction history (date, type, amount)

Summary statistics using NumPy (total deposits, withdrawals, average transaction)

✅ User Interaction

Interactive menu-driven interface

Smooth navigation with loops & conditions

✅ Error Handling

Input validation for positive amounts

Prevent withdrawal beyond available balance

Handle invalid account numbers

✅ Optional Bonus (if implemented)

User login with username & password

Use of lambda functions for quick calculations

# 🛠 Technologies Used
Python 3.x

Pickle (for saving/loading account data)

NumPy (for summary statistics)

datetime (for transaction timestamps)

# 📂 Project Structure
bash
Copy
Edit
bank_management/
│
├── bank_system.ipynb    # Main Jupyter Notebook
├── accounts.pkl         # Pickle file storing account data
├── transactions.pkl     # Pickle file storing transaction history
└── README.md            # Project documentation
# 🚀 How to Run
1️⃣ Clone the Repository
git clone https://github.com/your-username/bank-account-management.git
cd bank-account-management

2️⃣ Install Requirements (NumPy)
pip install numpy

3️⃣ Run the Notebook
Open bank_system.ipynb in Jupyter Notebook and run all cells.

# 🧑‍💻 Usage
When you run the program, you’ll see an interactive menu:

==== Bank Account Management ====
1. Open a New Account
2. View Account Details
3. Deposit Money
4. Withdraw Money
5. Transfer Money
6. View Transaction History
7. Exit
Enter your choice:
Follow the prompts to create accounts, perform transactions, or view reports.

# 📊 Example Output
✅ Creating a new account:

yaml
Copy
Edit
Enter account holder's name: Alice
Account type (savings/current): savings
Initial balance: 5000
✅ Account created successfully! Your Account Number is 1001
✅ Depositing money:

yaml
Copy
Edit
Enter account number: 1001
Enter amount to deposit: 2000
✅ Deposit successful! New balance: 7000
✅ Viewing transaction history:

Date        | Transaction | Amount
2025-07-26  | Deposit     | 2000
2025-07-26  | Withdraw    | 500

# 📌 Future Improvements
Implement a login system for multiple users

Add a GUI version using Tkinter or PyQt

Support for interest calculation

# 🤝 Contributing
Feel free to fork this repository and submit pull requests with improvements!

# 📝 License
This project is for educational purposes and is free to use.

#############################################################################################

# 🛒 Super Market Billing System

A simple Python-based billing system for a supermarket, built using Jupyter Notebook. This project simulates a point-of-sale (POS) experience where customers can select items from a predefined menu and receive a bill based on their choices.

## 📌 Features

- Predefined supermarket inventory with 5 common items
- Price calculation based on quantity
- User-friendly prompts via console (text input)
- Simple, modular Python code using lists and dictionaries
- Easily extendable to include stock management, discounts, categories, and more

## 🧾 Sample Menu

```python
menu = [
    {"sr_no": 1, "name": "Whole Milk (1 Gallon)", "price": 3.49},
    {"sr_no": 2, "name": "White Bread (Loaf)", "price": 2.49},
    {"sr_no": 3, "name": "Brown Eggs (Dozen)", "price": 3.29},
    {"sr_no": 4, "name": "Chicken Breast (per lb)", "price": 5.29},
    {"sr_no": 5, "name": "Fuji Apples (per lb)", "price": 1.49}
]
