# While-Loop-For-Loop-and-Function--Python
Python Assignment 3 – While Loop, For Loop, and Function
## Project Overview

This project is part of the **Data Analytics (DA) – Module 4** Python assignment.

The objective of this assignment is to develop a basic understanding of **loops, control statements, and functions in Python**. The assignment includes three practical programs based on real-world examples:

1. Number Guessing Game using a `while` loop
2. Multiplication Table Generator using a `for` loop
3. BMI Calculator using a function

The programs were developed and executed using **Jupyter Notebook**.

---

## Objectives

The main objectives of this assignment are:

* To understand and implement a `while` loop.
* To understand and implement a `for` loop.
* To use the `range()` function.
* To understand control statements such as `break`, `continue`, and `else`.
* To create and use Python functions.
* To practice user input and output.
* To develop logical problem-solving skills using Python.
* To apply Python programming concepts to simple real-world problems.

---

## Tools and Technologies

* **Programming Language:** Python
* **Development Environment:** Jupyter Notebook
* **Python Concepts:** While Loop, For Loop, Functions, Control Statements
* **Python Library:** Random

---

# Tasks Performed

## Task 1: Number Guessing Game

### Problem Statement

A simple number guessing game was created using a `while` loop. The program generates a random number between **1 and 10**, and the user gets a maximum of **3 attempts** to guess the correct number.

### Concepts Used

* `while` loop
* `if`, `elif`, and `else`
* `break`
* `continue`
* `random.randint()`
* User input
* Conditional statements

### How It Works

1. The `random` module is imported.
2. A random number between 1 and 10 is generated.
3. The number of attempts is set to 3.
4. The user is asked to enter a guess.
5. If the guess is outside the range 1 to 10, a message is displayed and `continue` skips the remaining statements in that iteration.
6. If the guess is greater than the secret number, the program displays **"Too high."**
7. If the guess is lower than the secret number, the program displays **"Too low."**
8. If the guess is correct, `break` is used to exit the loop.
9. The `while` loop `else` block displays **"Better luck next time!"** when the user uses all attempts without guessing correctly.

### Example

```text
Guess the number (between 1 and 10): 2
Too low. Try again.

Guess the number (between 1 and 10): 15
Your guess is out of range. Please guess a number between 1 and 10.

Guess the number (between 1 and 10): 5
Too high. Try again.

Guess the number (between 1 and 10): 3
Congratulations! You guessed the correct number.
```

---

# Task 2: Multiplication Table Generator

### Problem Statement

A Python program was created to generate a multiplication table from **1 to 10** for a number entered by the user.

### Concepts Used

* `for` loop
* `range()` function
* User input
* Arithmetic operators
* Formatted output

### How It Works

1. The user enters a number.
2. A `for` loop is used to iterate from 1 to 10.
3. In each iteration, the entered number is multiplied by the current loop value.
4. The result is displayed in the format:

```text
number x i = result
```

### Example

For the input `5`, the program produces:

```text
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

---

# Task 3: BMI Calculator

### Problem Statement

A BMI Calculator was developed using a Python function. The program calculates Body Mass Index based on the user's weight and height.

### BMI Formula

```text
BMI = Weight (kg) / Height (m)²
```

### Concepts Used

* Function creation
* Function parameters
* `return` statement
* User input
* Arithmetic operations
* Formatted output

### Function Used

```python
def calculate_bmi(weight, height):
    return weight / (height ** 2)
```

### How It Works

1. The `calculate_bmi()` function is defined.
2. The user enters their weight in kilograms.
3. The user enters their height in meters.
4. The function calculates the BMI using the given formula.
5. The calculated BMI is displayed with two decimal places.

### Example

```text
Enter your weight in kg: 58
Enter your height in meters: 1.62

Your BMI is: 22.10
```

---

# Python Concepts Demonstrated

| Concept                | Application                                          |
| ---------------------- | ---------------------------------------------------- |
| While Loop             | Number Guessing Game                                 |
| For Loop               | Multiplication Table                                 |
| Range Function         | Iterating from 1 to 10                               |
| Break                  | Exiting the guessing game when the answer is correct |
| Continue               | Skipping invalid guesses                             |
| Else                   | Displaying a message when attempts are exhausted     |
| Function               | BMI calculation                                      |
| Parameters             | Weight and height in BMI function                    |
| Return                 | Returning the calculated BMI                         |
| Random Module          | Generating the secret number                         |
| User Input             | Taking values from the user                          |
| Conditional Statements | Checking guesses and conditions                      |

---

# Project Structure

```text
Python-Assignment-3/
│
├── Python_Assignment_3.ipynb
│
└── README.md
```

### File Description

**Python_Assignment_3.ipynb**
Contains the complete implementation, execution, and output of all three tasks.

**README.md**
Contains the project overview, objectives, tools, task descriptions, concepts used, and project structure.

---

# Learning Outcomes

After completing this assignment, I gained practical knowledge of:

* Using `while` loops for repeated execution.
* Using `for` loops for iteration.
* Using `range()` to control loop iterations.
* Applying `break` and `continue` in loops.
* Understanding the `else` block with a `while` loop.
* Creating functions with parameters.
* Returning values from functions.
* Using Python's `random` module.
* Taking user input and displaying formatted output.
* Applying logical thinking to solve programming problems.

---

# Conclusion

This assignment provided practical experience with fundamental Python programming concepts. The **Number Guessing Game** helped demonstrate the use of a `while` loop and control statements such as `break`, `continue`, and `else`. The **Multiplication Table Generator** demonstrated the use of a `for` loop and the `range()` function. The **BMI Calculator** provided practice in creating functions, passing parameters, and returning calculated values.

Overall, these tasks strengthened my understanding of Python programming fundamentals and logical problem-solving skills, which are important for further learning in **Data Analytics and Python**.

By
Sharulatha.B 
  ( Aspiring Data Analyst )

