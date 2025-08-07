ATM Machine Simulation in Java
==============================

This project is a complete simulation of an ATM (Automated Teller Machine) built in Java.
It includes both console-based and GUI-based interfaces and implements core banking functionalities like 
PIN authentication, balance check, deposit, withdraw, and transaction history.

Built With:
- Java (JDK 8+)
- Java Swing (for GUI version)
- Object-Oriented Programming

Features:
---------
- PIN Authentication: Console ✅ | GUI ✅
- Check Balance: Console ✅ | GUI ✅
- Withdraw Funds: Console ✅ | GUI ✅
- Deposit Funds: Console ✅ | GUI ✅
- View Transaction History: Console ✅ | GUI ✅ (scrollable)
- Input Validation/Error Handling: Console ✅ | GUI ✅
- Real-Time UI Feedback: Console ❌ | GUI ✅

Project Structure:
------------------
BankAccount.java       # Core logic for deposit, withdraw, balance, history, PIN
ATM.java               # GUI version using Java Swing
LoginScreen.java       # PIN login GUI screen
ATMMain.java           # Main class to run the GUI app

PIN Authentication:
--------------------
- The account has a predefined PIN (e.g., 1234)
- User is prompted to enter the PIN on the GUI login screen
- After 3 invalid attempts, the app exits
- Upon successful login, ATM menu is launched

Transaction Logging:
--------------------
- Every deposit/withdraw action is logged
- Timestamped entries are stored in memory
- Accessible through the "Transaction History" feature
- Scrollable in the GUI

How to Run:
-----------
1. Compile: javac *.java
2. Run:     java ATMMain

Future Improvements:
--------------------
- Add database (JDBC) integration for persistent accounts
- Enable multiple account holders
- Add admin dashboard to reset PINs or manage users
- Include ATM card simulation with card number & CVV

Concepts Practiced:
-------------------
- Encapsulation and OOP design
- Event-driven programming with Swing
- Real-time input validation
- Data handling and formatting
- Modular Java application design
