# ATM Simulation (Python GUI)

**Author:** Dan Quackenbush  

This project simulates a simple ATM (Automated Teller Machine) with a graphical user interface.  
It allows a user to log in with a name and PIN, then perform **balance checks**, **deposits**, and **withdrawals** on a savings account.

---

##  Description

The ATM program demonstrates the use of:
- **Object-Oriented Programming (OOP)** (Bank, SavingsAccount, ATM classes)
- **GUI programming** with [BreezyPythonGUI](http://breezypythongui.com/)
- **Data persistence** using Python’s `pickle` module to save/load accounts

### Classes & Files
- **`atm.py`**  
  Provides the GUI for interacting with accounts. Handles login/logout and connects user actions to the bank model.

- **`bank.py`**  
  Manages a collection of accounts in a dictionary keyed by `name/pin`. Supports adding, removing, retrieving, and saving accounts.

- **`savingsaccount.py`**  
  Defines the `SavingsAccount` class with fields for account holder’s name, PIN, and balance. Provides `deposit`, `withdraw`, `getBalance`, and `computeInterest`.

- **`breezypythongui.py`**  
  GUI framework used to simplify building windows and widgets on top of Tkinter.

---

## How to Run
Place all dowloads in the same folder and navigate to that folder via windows command prompt
use command: python atm.py

2. **Download the project files**  
   Place these files in the same folder:
