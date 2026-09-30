ATM Management System 🏧

A simple ATM Management System built using Python. This project allows users to create bank accounts, securely log in using a PIN, check their balance, deposit and withdraw money, and view their recent transactions.

Features

Create a new bank account

Automatically generate a unique account number

4-digit PIN authentication

Maximum 3 login attempts

View account details

Check account balance

Deposit money

Withdraw money

View the last 5 transactions

Store account data using JSON

Automatic transaction date and time

Logout functionality

Technologies Used

Python

JSON – for storing account data

Random – for generating account numbers

OS – for checking the data file

Datetime – for recording transaction date and time

Project Structure
ATM-Management-System/
│
├── atm.py
├── accounts.json
└── README.md


accounts.json is automatically created by the program when account data is saved.

How to Run
1. Clone the repository
git clone https://github.com/your-username/ATM-Management-System.git

2. Open the project folder
cd ATM-Management-System

3. Run the Python program
python atm.py

How It Works

Select Create Account to create a new bank account.

Enter your personal and bank details.

Set a 4-digit PIN.

The system generates a unique account number.

Use the account number and PIN to log in.

After login, you can:

View Account Details

Check Balance

Deposit Money

Withdraw Money

View Mini Statement

Logout

Data Storage

The project uses a JSON file named accounts.json to store account information, including:

Account number

Name

Date of birth

Account type

PIN

Balance

Branch details

IFSC code

Transaction history

Important Note

This project is created for learning and educational purposes. It is a basic console-based ATM simulation and should not be used for handling real banking or financial data.

Future Improvements

Add a graphical user interface (GUI)

Encrypt PINs and sensitive information

Add fund transfer functionality

Add account deletion

Add password/PIN change option

Add transaction receipt generation

Add database support such as MySQL or SQLite

Author

Your Name = _Vinay Kumar_
