# Java Banking System (Console-Based)

## Project Overview
This project is a console-based Banking Management System developed in Java using Object-Oriented Programming (OOP) concepts.  
It simulates basic banking operations for Savings and Current accounts and is designed for academic learning purposes.

The project demonstrates:
- Inheritance
- Method overriding
- Encapsulation
- Basic input validation
- Modular class design

---

## Project Structure
Bank-Account-Management-System/
               ├── Account.java
               ├── Savings.java
               ├── Current.java
               ├── Bank.java

---

## Class Description

### Account (Base Class)
The Account class is the parent class for all account types.

Attributes:
- Account number
- Account holder name
- Balance

Methods:
- deposit(double amount)
- withdraw(double amount)
- getBalance()

---

### Savings (Derived Class)
Inherits from Account and represents a savings account.

Features:
- Limited withdrawal amount
- Deposit and withdrawal validation
- Can be extended to include interest calculation

---

### Current (Derived Class)
Inherits from Account and represents a current account.

Features:
- Higher deposit and withdrawal limits
- Suitable for frequent transactions
- Overridden deposit and withdraw methods

---

### Bank (Main Class)
- Contains the main() method
- Entry point of the application
- Handles user interaction and banking operations

---

## Features Implemented
- Create Savings and Current accounts
- Deposit money with limit checks
- Withdraw money with validation
- Display account balance
- Uses OOP principles like inheritance and polymorphism
- Transaction history details

---

## Author
Sheikh Aalam  
B.Tech (Information Technology)
