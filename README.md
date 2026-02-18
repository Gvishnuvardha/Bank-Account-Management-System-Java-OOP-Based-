# Bank-Account-Management-System-Java-OOP-Based-
A console-based banking application built using Core Java that supports deposit, withdrawal, transaction history, and custom exception handling using OOP principles.


#  Bank Management System (Java)

A simple console-based banking application built using **Core Java**.  
This project demonstrates the use of **OOP concepts, Exception Handling, Collections, and User Input Handling**.

---

##  Features

-  Check Account Balance
-  Deposit Money
-  Withdraw Money
-  Custom Exception Handling (Insufficient Balance)
-  View Previous Transaction
-  View Complete Transaction History
-  Input Validation
-  Menu Driven CLI Interface

---

##  Technologies Used

- Java
- OOP Concepts
- Exception Handling
- ArrayList (Collections Framework)
- Scanner (User Input)

---

##  Concepts Used

- Encapsulation
- Custom Exception Class
- Method Overloading
- Control Statements (Switch, Loops)
- Input Validation
- Collections (ArrayList)

---

##    How To Run

1. Clone the repository
2. Compile the code in online java compiler files
3. Run the code

---
##  How It Works

1. User enters account name and ID.
2. Menu is displayed with options:
   - A → Check Balance
   - B → Deposit
   - C → Withdraw
   - D → Previous Transaction
   - E → Transaction History
   - F → Exit
3. All transactions are stored in an ArrayList.
4. Custom Exception is thrown if withdrawal amount exceeds balance.

---

##  Project Structure

BankManagementSystem/
│
├── src/
│   ├── Main.java
│   ├── BankAccount.java
│   └── InsufficientBalanceException.java
│
├── README.md
└── .gitignore

---

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                                                      (UML Design)


+----------------------------------+
|     InsufficientBalanceException |
+----------------------------------+
| - message : String               |
+----------------------------------+
| + InsufficientBalanceException() |
+----------------------------------+


+----------------------------------+
|           BankAccount            |
+----------------------------------+
| - balance : int                  |
| - prevTransaction : int          |
| - name : String                  |
| - id : String                    |
| - transactionHistory : ArrayList |
+----------------------------------+
| + BankAccount(name, id)          |
| + getBalance() : int             |
| + deposit(amount) : void         |
| + withdraw(amount) : void        |
| + prevTransaction() : void       |
| + showTransactionHistory() : void|
| + showMenu() : void              |
+----------------------------------+


+---------------------------+
|           Main            |
+---------------------------+
| + main(args[]) : void     |
+---------------------------+




---

##  Author

Vishnuvardhan Reddy  
B.Tech CSE (2026)  
Aspiring Java Backend Developer
