Yes — you mean you want the **actual Markdown text**, without the extra formatting that makes it look like a code block.

Here it is:

# Bank Management System

A Python-based console banking application developed as part of the **Introduction to Problem Solving and Programming** course at **VIT Bhopal**.

The application provides basic banking operations through a menu-driven interface and stores account information persistently in a JSON file.

## Features

* Create a new bank account
* Generate a unique 5-digit account number
* Set a 4-digit PIN
* Make an initial deposit
* Login using account number and PIN
* Check account balance
* Deposit money
* Withdraw money
* Prevent withdrawals when funds are insufficient
* View account details
* Store account data persistently in `bank_data.json`
* Validate user input and handle errors

## Technologies and Tools

* **Python 3**
* **JSON** for persistent data storage
* Python built-in modules:

  * `json`
  * `random`
  * `sys`
  * `os`
* Git and GitHub

No external Python packages are required.

## Project Structure

```text
Banking_Management_System/
├── main.py
├── bank_data.json
├── README.md
└── Bank-Management-System-README.pdf
```

## Requirements

* Python 3
* A Python-supported IDE or terminal
* Project files available on your computer

Check your Python installation:

```bash
python --version
```

Or:

```bash
python3 --version
```

## Installation and Setup

Clone the repository:

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

Move into the project directory:

```bash
cd Bank-Management-System
```

Alternatively, download the repository as a ZIP file and extract it.

Make sure `main.py` is present in the project directory.

## How to Run

Run the Python program:

```bash
python main.py
```

If your system uses `python3`:

```bash
python3 main.py
```

## Basic Usage

### Creating an Account

1. Select **Create New Account**.
2. Enter your full name.
3. Enter a 4-digit PIN.
4. Enter the initial deposit amount.
5. The system generates a unique account number.
6. Save the account number for future login.

### Logging In

1. Select **Login to Existing Account**.
2. Enter your account number.
3. Enter your PIN.
4. After successful authentication, the account dashboard appears.

### Account Dashboard

After login, the following operations are available:

1. Check Balance
2. Deposit Money
3. Withdraw Money
4. View Account Details
5. Logout

## Input Validation and Error Handling

The application handles:

* Empty names
* Invalid PINs
* Invalid numerical input
* Negative amounts
* Invalid menu choices
* Insufficient funds
* Corrupted JSON data
* Program interruption

## Testing

| Test                              | Expected Result                         |
| --------------------------------- | --------------------------------------- |
| Create account with valid details | Account is created                      |
| Enter an invalid PIN              | Account creation is rejected            |
| Login with correct credentials    | Login successful                        |
| Login with incorrect PIN          | Access denied                           |
| Check balance                     | Current balance is displayed            |
| Deposit a positive amount         | Balance increases                       |
| Enter an invalid deposit          | Deposit is rejected                     |
| Withdraw within available balance | Balance decreases                       |
| Withdraw more than balance        | Transaction is rejected                 |
| View account details              | Account information is displayed        |
| Restart the program               | Previous account data remains available |

## Project Workflow

Start → Load Account Data → Display Main Menu → Create New Account / Login / Exit → Verify Account Number & PIN → Account Dashboard → Check Balance / Deposit / Withdraw / Account Details / Logout → Save Updated Data → Logout / Exit

## Documentation

The complete project documentation, including detailed features, screenshots, testing information, workflow, and future enhancements, is available here:

[View the complete project documentation (PDF)](Bank-Management-System-README.pdf)

## Future Enhancements

* Transaction history
* Fund transfer between accounts
* Multiple account types
* Bank statements
* Interest calculation
* Graphical user interface
* Database integration
* Improved authentication and security
* Search and filtering of transactions

## Author

**Tom Jaison**

* **Course:** Introduction to Problem Solving and Programming
* **Institution:** VIT Bhopal
* **Project:** Bank Management System
* **Academic Year:** 2026
