# 🧮 Fundamental Booster – Personal Data Collector

A beginner-friendly, console-based Python application that collects basic personal information from a user, demonstrates core Python data types and built-in functions, and provides insight into how Python stores data in memory.

---

## 📖 Project Description

**Fundamental Booster – Personal Data Collector** is a simple command-line Python application designed to help beginners understand the fundamentals of Python programming. It guides users through entering their name, age, height, and phone number, then displays each value along with its **data type** and **memory address** using Python's built-in `type()` and `id()` functions.

The program also calculates the user's approximate birth year based on their age, making it an excellent beginner project for learning Python fundamentals.

---

## ✨ Features

- 👋 Displays a friendly welcome message.
- ⌨️ Collects the user's name, age, height, and phone number.
- 🔄 Converts user input into appropriate data types.
- 🔍 Displays each variable's data type using `type()`.
- 🧠 Displays each variable's memory address using `id()`.
- 🎂 Calculates the user's approximate birth year.
- 📋 Displays all collected information in a clean, formatted output.
- 🙏 Ends with a thank-you message.

---

## 🐍 Python Concepts Used

- `input()`
- `print()`
- Variables
- Data Types (`str`, `int`, `float`)
- Type Casting (`int()`, `float()`)
- `type()`
- `id()`
- Arithmetic Operators
- f-Strings
- Sequential Program Flow

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.x | Programming Language |
| Console / Terminal | Application Execution |

No external libraries are required.

---

## 🚀 How to Run

### Prerequisites

- Python 3.x

Check your Python version:

```bash
python --version
```

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/fundamental-booster-.git
```

Move into the project folder:

```bash
cd fundamental-booster-
```

Run the program:

```bash
python fundamental_booster.py
```

---

## 💻 Sample Input

```
Enter your name: Darshan
Enter your age: 20
Enter your height (in cm): 175.5
Enter your number: 18
```

---

## 💻 Sample Output

```
Welcome to Fundamental Booster – Personal Data Collector!

Name: Darshan
Type: <class 'str'>
Memory Address: 140234567891232

Age: 20
Type: <class 'int'>
Memory Address: 9793120

Height: 175.5
Type: <class 'float'>
Memory Address: 140234567892128

Phone Number: 18
Type: <class 'int'>
Memory Address: 140234567893120

Your approximate birth year is: 2006

Thank you for using Fundamental Booster!
```

> **Note:** Memory addresses change every time the program runs because Python manages memory dynamically.

---
##  Video

Link:

---
## 🎯 Learning Objectives

This project helps beginners understand:

- Taking user input
- Variable declaration
- Data types
- Type conversion
- Arithmetic operations
- Using `type()` and `id()`
- Formatted output using f-strings

---

## 📂 Project Structure

```
fundamental-booster-/
│
├── fundamental_booster.py
└── README.md
```

---

## ⚠️ Assumptions

- Users enter valid input.
- No input validation is implemented.
- Birth year is calculated as:

```
Current Year - Age
```

- The current year used is **2026**.

---

## 🔮 Future Improvements

- ✅ Add input validation.
- ✅ Add `try-except` error handling.
- 📱 Validate phone number format.
- 📄 Save user data to a file.
- 🖥️ Build a Tkinter GUI.
- 🌐 Convert the project into a Flask web application.
- 📅 Use the system date for birth-year calculation.

---

## 📬 Contact
Darshan Variya
****

📧 Email: **darshanvariya5@gmail.com**

🐙 GitHub: https://github.com/darshanvariya5-collab

---

## ⭐ If you found this project helpful, don't forget to Star the repository!

Happy Coding! 🚀
