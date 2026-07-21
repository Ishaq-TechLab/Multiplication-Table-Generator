# Java Multiplication Table Generator

## Overview

The **Multiplication Table Generator** is a simple console-based Java application that generates the multiplication table for a number entered by the user. The program displays the multiplication table from **1 through 12**, making it a useful beginner project for practicing loops and arithmetic operations.

This project demonstrates user input, `for` loops, variables, and formatted console output in Java.

## Features

* Accepts a number from the user
* Generates the multiplication table from **1 to 12**
* Displays each multiplication step clearly
* Simple and easy-to-use console interface

## Technologies Used

* Java
* `Scanner` class for user input
* `for` loop
* Console-based application

## Project Structure

```text
day5/
└── MultiplicationTablleGenerator.java
```

## How It Works

1. The program prompts the user to enter a number.
2. The entered number is stored in a variable.
3. A `for` loop iterates from **1 to 12**.
4. During each iteration:

   * The program multiplies the entered number by the current loop value.
   * The result is displayed in multiplication table format.

## Example Output

```text
Enter a Number to Print its Multiplication Table
7

The Multiplication Table of 7:

7 X 1 = 7
7 X 2 = 14
7 X 3 = 21
7 X 4 = 28
7 X 5 = 35
7 X 6 = 42
7 X 7 = 49
7 X 8 = 56
7 X 9 = 63
7 X 10 = 70
7 X 11 = 77
7 X 12 = 84
```

## How to Run

### Compile

```bash
javac day5/MultiplicationTablleGenerator.java
```

### Run

```bash
java day5.MultiplicationTablleGenerator
```

## Learning Concepts Demonstrated

* Java classes and methods
* Variables and data types
* User input using the `Scanner` class
* `for` loops
* Arithmetic operations
* Console input and output

## Possible Improvements

* Allow users to specify the maximum multiplier instead of always stopping at 12.
* Generate multiplication tables for multiple numbers in one execution.
* Validate user input to handle non-numeric values.
* Format the output into aligned columns for improved readability.
* Allow users to continue generating tables without restarting the application.
* Create a graphical user interface (GUI) using Java Swing or JavaFX.

## Notes

* The program generates multiplication tables from **1 through 12**.
* The entered value can be positive, negative, or zero.
* Each multiplication result is displayed on a new line.

## Author
Ishaq Taj
QA Automation Engineer | Java | Selenium | Test Automation
