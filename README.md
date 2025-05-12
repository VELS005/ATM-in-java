# ATM Simulation in Java

This project is a command-line-based ATM (Automated Teller Machine) simulation written in Java. It allows users to log in, view balances, withdraw, deposit, and transfer funds between checking and savings accounts.

## Features

- User login with customer number and PIN
- Create new account functionality
- Check balance for checking and savings accounts
- Deposit and withdraw funds
- Transfer funds between accounts
- Error handling for invalid inputs

## Project Structure

- `ATM.java`: Entry point of the application. Displays a welcome message and invokes the main menu.
- `OptionMenu.java`: Handles user interaction, login, account creation, and menu navigation.
- `Account.java`: Manages account-related data and operations like deposit, withdrawal, transfer, and balance checks.
