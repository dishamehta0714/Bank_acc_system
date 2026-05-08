Bank Management System - README
Project Title

Bank-account-system:  https://onlinegdb.com/iljPf_Y7N


Bank Management System using C++ OOP Concepts

Introduction

This project is a simple Bank Management System developed in C++ using Object Oriented Programming (OOP) concepts.

The system allows users to:

Create different types of bank accounts
Deposit money
Withdraw money
Check balance
Calculate interest
Display account details

This project demonstrates important OOP concepts like:

Class and Object
Inheritance
Encapsulation
Polymorphism
Function Overriding
Virtual Functions
Features
1. Savings Account
Supports interest calculation
User can deposit and withdraw money
Calculates interest based on interest rate
2. Checking Account
Supports overdraft facility
User can withdraw extra money within overdraft limit
3. Fixed Deposit Account
Calculates fixed deposit interest
Withdrawal is restricted
OOP Concepts Used
Concept	Description
Class	Blueprint for creating objects
Object	Instance of class
Inheritance	Child class inherits parent class properties
Encapsulation	Data hiding using private members
Polymorphism	Same function behaves differently
Virtual Function	Enables runtime polymorphism
Function Overriding	Redefining parent class function in child class
Classes Used
1. BankAccount (Base Class)

Contains:

Account Number
Account Holder Name
Balance
Deposit Function
Withdraw Function
Display Function
2. SavingsAccount (Derived Class)

Additional Feature:

Interest Rate
Interest Calculation
3. CheckingAccount (Derived Class)

Additional Feature:

Overdraft Limit
Overdraft Checking
4. FixedDepositAccount (Derived Class)

Additional Feature:

Fixed Deposit Term
FD Interest Calculation
Technologies Used
Language: C++
Compiler: g++ / Turbo C++ / VS Code
Concepts: OOP
How to Run the Program
Step 1:

Open terminal or compiler

Step 2:

Compile the program

g++ filename.cpp -o bank
Step 3:

Run the program

./bank
Sample Menu
--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Display Account Info
5. Calculate Interest
0. Exit
Sample Output
Enter Account Number: 101
Enter Account Holder Name: Disha
Enter Initial Balance: 5000

Select Account Type:
1. Savings Account
2. Checking Account
3. Fixed Deposit Account

Enter Interest Rate (%): 5

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Display Account Info
5. Calculate Interest
0. Exit
Advantages of Project
Easy to understand
Demonstrates real-life banking system
Good practice for OOP concepts
Beginner friendly project
Future Improvements
Add file handling
Add password security
Add multiple account storage
Add transaction history
Add GUI interface
Conclusion

This project helps beginners understand how Object Oriented Programming works in real-world applications. It covers important banking operations and demonstrates inheritance, polymorphism, encapsulation, and virtual functions in C++.

Author

Developed By: Disha Mehta
Course: B.Sc. Data Science & Analytics
Technology: C++ OOP Programming
