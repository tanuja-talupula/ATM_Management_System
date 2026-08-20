# ATM Management System

A console-based **ATM Management System** developed using Python. The project simulates basic ATM operations such as user authentication, balance inquiry, cash deposit, cash withdrawal, PIN change, and logout.

## 📌 Project Overview

The ATM Management System is designed to demonstrate the use of **Python Object-Oriented Programming (OOP)**, **JSON file handling**, **exception handling**, and **input validation**.

User account information is stored in a JSON file. After successful authentication using an account number and PIN, users can perform different banking operations through a menu-driven interface.

## ✨ Features

* 🔐 Account number and PIN authentication
* 💰 Balance inquiry
* 💵 Cash deposit
* 🏧 Cash withdrawal
* 🔑 PIN change
* 💾 JSON-based data storage
* ⚠️ Input validation and exception handling
* 🚪 Secure logout
* 🔄 Automatic saving of updated account information

## 🛠️ Technologies Used

* **Python**
* **Object-Oriented Programming (OOP)**
* **JSON**
* **File Handling**
* **Exception Handling**

## 📂 Project Structure

```text
ATM-Management-System/
│
├── ATM-Management-System.ipynb
├── users.json
└── README.md
```

### Files

**`ATM-Management-System.ipynb`**
Contains the complete Python implementation of the ATM Management System.

**`users.json`**
Stores sample user account information such as account number, name, PIN, and balance.

**`README.md`**
Contains the project documentation.

## ⚙️ How the System Works

### 1. Load User Data

The program loads account information from the JSON file using Python's `json` module.

### 2. User Authentication

The user enters:

* Account Number
* PIN

The system verifies the entered credentials against the stored account information.

### 3. ATM Menu

After successful login, the user can select from the following operations:

```text
1. Balance Inquiry
2. Cash Deposit
3. Cash Withdrawal
4. Change PIN
5. Logout
```

### 4. Balance Inquiry

Displays the current account balance.

### 5. Cash Deposit

The user enters the amount to deposit. The system validates the amount, updates the balance, and saves the updated information to the JSON file.

### 6. Cash Withdrawal

The user enters the withdrawal amount. The system checks whether the amount is valid and whether sufficient balance is available before completing the transaction.

### 7. PIN Change

The user enters the current PIN and provides a new four-digit PIN. The system validates the new PIN and saves the updated PIN to the JSON file.

### 8. Logout

The user can safely exit the ATM menu by selecting the logout option.

## 🧠 Python Concepts Demonstrated

This project demonstrates the following concepts:

* Classes and Objects
* Constructors (`__init__`)
* Methods
* `self` keyword
* Conditional statements
* Loops
* Functions
* Exception handling
* File handling
* JSON data processing
* Input validation
* Modular programming

## 🔒 Input Validation

The project includes validation to handle common user errors:

* Invalid account number or PIN
* Invalid deposit amount
* Invalid withdrawal amount
* Insufficient account balance
* Invalid four-digit PIN
* PIN confirmation mismatch
* Missing JSON file
* Invalid JSON data

## ▶️ How to Run

### Using Google Colab

1. Open `ATM-Management-System.ipynb` in Google Colab.
2. Upload the `users.json` file to the Colab environment.
3. Run the notebook cells.
4. Enter the JSON filename when prompted.
5. Enter the account number and PIN.
6. Select an operation from the ATM menu.

### Using Jupyter Notebook

1. Download the project files.
2. Open `ATM-Management-System.ipynb` using Jupyter Notebook or JupyterLab.
3. Make sure `users.json` is in the same working directory.
4. Run the notebook cells.
5. Follow the instructions displayed in the console.

## 🧪 Sample Account

For demonstration purposes, the JSON file can contain sample account information such as:

```json
{
    "1001": {
        "name": "Demo User",
        "pin": "1234",
        "balance": 5000
    }
}
```

> **Note:** The account details above are only sample data for demonstration. Do not store real banking credentials or sensitive information in a public repository.

## 🚀 Future Improvements

The project can be further improved by:

* Connecting the system to a MySQL or SQL Server database
* Adding transaction history
* Adding account creation functionality
* Adding fund transfer functionality
* Adding daily withdrawal limits
* Implementing stronger PIN security
* Adding password/PIN hashing
* Developing a graphical user interface
* Adding unit testing

## 👩‍💻 Author

**Tanuja Talupula**

B.Tech Bioinformatics

