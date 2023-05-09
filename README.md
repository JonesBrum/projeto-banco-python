# Bank Account Management System
This is a Python code that simulates a simple banking system. It presents some classes and methods that allow the creation of checking accounts, withdrawals, deposits, and other banking transactions.

Classes:

Account: This is the base class for all types of accounts. It contains methods for depositing and withdrawing money, checking the account balance, and printing the account statement.
CheckingAccount: This is a subclass of Account that adds a monthly fee and a limit to the number of transactions that can be performed in a month.
SavingsAccount: This is a subclass of Account that adds an interest rate and a minimum balance requirement.
Methods:

create_account(): This method creates a new account by prompting the user for the account type, name, and initial balance.
make_deposit(): This method deposits money into an account by prompting the user for the account number and the deposit amount.
make_withdrawal(): This method withdraws money from an account by prompting the user for the account number and the withdrawal amount.
print_statement(): This method prints the account statement for a given account by prompting the user for the account number.
Usage:
To use this code, simply run the file "banking_system.py" and follow the prompts to create accounts, make deposits and withdrawals, and print account statements.

Contributing:
Contributions are welcome. Feel free to submit pull requests or open issues on GitHub.

License:
This code is released under the MIT License. See the LICENSE file for details.
