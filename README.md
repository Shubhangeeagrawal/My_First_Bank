### My_First_Bank
This project have a basic banking system in Java, consisting of two main classes: Account and FirstBank.
# Purpose
The provided code is designed to simulate basic operations of a banking system. It allows users to create an account, deposit and withdraw money, check their balance, view their last transaction, and calculate interest over a period of time.

### Components
#1. Account Class
The Account class represents a bank account. It encapsulates all necessary data and functions related to a bank account.

# Attributes
*balance: Keeps track of the current amount of money in the account.
*previousTransaction: Stores the amount of the most recent transaction (positive for deposits, negative for withdrawals).
*customerName: Stores the name of the account holder.
*customerID: Stores the unique identifier for the account holder.

# Constructor
The constructor initializes the account with the customer's name and ID. This sets up a new account instance ready for transactions.

# Methods
*deposit(int amount): Adds a specified amount to the account balance and records the transaction.
*withdraw(int amount): Subtracts a specified amount from the account balance and records the transaction.
*getPreviousTransaction(): Displays details of the last transaction (deposit or withdrawal).
*calculateInterest(int years): Calculates and displays the new balance after applying interest over a specified number of years. The interest rate is given as a percentage and converted to a decimal for calculations.
*showMenu(): Provides a user interface through the console. It displays a menu of options (check balance, deposit, withdraw, view previous transaction, calculate interest, exit) and allows the user to perform these operations interactively.

### Main Class
# FirstBank Class
The FirstBank class contains the main method, which is the entry point of the program.

# Functionality
It creates instances of the Account class, initializing accounts with specific customer names and IDs.
It invokes the showMenu method on an account instance, which allows the user to interact with their account through a menu-driven interface.
# How It Works
*Initialization: When the program starts, it initializes bank accounts with specific customer details (name and ID).
*User Interaction: Through the showMenu method, the user can:
-Check their account balance.
-Deposit money into their account.
-Withdraw money from their account.
-View details of their most recent transaction.
-Calculate the balance after applying interest for a specified number of years.
*Loop: The menu is displayed repeatedly until the user chooses to exit, allowing multiple operations in a single session.
