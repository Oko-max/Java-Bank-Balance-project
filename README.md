# Java-Bank-Balance-project

Simple Bank Application
This is a simple console-based Java application that simulates basic bank account functionalities like logging in, checking balance, depositing funds, and withdrawing funds.

Features
User Authentication: Secure login with a predefined username and password, with a limited number of attempts.

Check Balance: View the current balance of the account.

Deposit Funds: Add money to the account.

Withdraw Funds: Deduct money from the account, with checks for sufficient funds.

Input Validation: Handles invalid input for deposit and withdrawal amounts.

User-Friendly Interface: Simple menu-driven interaction.

BankAccount account = new BankAccount("yourNewUsername", "yourNewPassword", 1000.00);
BankAccount account = new BankAccount("user123", "password123", 500.00); // New initial balance
