# ATM Simulator in C++
Table of Contents
  Introduction
  Project Overview
  Features
  Software Tool
  Code Details
  Installation
  Usage
  Contributing
  License
  Contact
  
# Introduction
This is a simple ATM Simulator program developed in C++ with ANSI-style graphics for command line output. The project simulates basic ATM functionalities like balance enquiry, withdrawal, deposit, PIN change, and mobile banking instructions. This project is an interactive terminal-based program that demonstrates basic C++ object-oriented programming concepts.

# Project Overview
This project is a basic simulation of an ATM machine using C++. It allows the user to perform basic banking transactions such as balance enquiry, withdrawal, adding money, changing the PIN, and accessing mobile banking instructions. The code includes decorative elements to improve the user experience.

# Features

PIN Authentication: A basic authentication system where users are prompted to enter a PIN. The default PIN is 2004.
Balance Enquiry: Allows users to check the current balance.
Cash Withdrawal: Users can withdraw an amount from their balance, ensuring they do not exceed their available balance.
Add Amount: Users can add a specific amount to their account balance.
Change PIN: Users can update their PIN.
Mobile Banking Instructions: Provides basic instructions for mobile banking, including security tips.
Multiple Attempts for PIN: The system allows users to enter their PIN, but locks them out after three failed attempts.
User Interface: Uses ANSI-style colors for a more user-friendly experience.

# SOFTWARE TOOL
Eclipse IDE

# Code Details
The project contains a single class ATM that handles all the functionalities. Each transaction type (Balance Enquiry, Withdrawal, Add Amount, etc.) is implemented as a separate function within the class. The program also features a decorated command-line interface using ASCII art and color codes to make it more engaging.

Main Components:
PIN Verification:

The user is prompted to enter their PIN (default: 2004).
Three attempts are allowed before locking the user out.
Menu Options:

Users can choose from the following options:
Balance Enquiry
Withdrawal
Add Amount
Change PIN
Mobile Banking Instructions
Exit
Decorative Interface:

Color-coded text and visual borders to enhance the user experience.

# Usage
Upon running the program, you will be greeted with a welcome message and asked to enter a PIN.
You can access the following functionalities after successful login:
Balance Enquiry: Check your current balance.
Withdrawal: Withdraw money if the balance is sufficient.
Deposit: Add money to your balance.
Change PIN: Update your PIN.
Mobile Banking: View instructions on mobile banking security.
Exit the ATM session after performing your transactions.
PIN Hint
The default PIN is set to 2004. You can change this within the program after logging in.

# Contributing
If you'd like to contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a Pull Request.

# License
This project is Open-source

# Contact
Author: Vikneshraj D
Feel free to reach out me vikneshraj2004@gmail/com

