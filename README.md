# Conditional Statements (If-Else, Switch-Case) Programs in C++

## 📌 Title of the Experiment
Implementation and demonstration of conditional control statements in C++ using If-Else and Switch-Case constructs.

## 🛠️ Tools Used
- Programming Language: C++
- IDE: Code:: VS Code 
- Operating System: Windows / Linux / macOS

## 📚 Theory

### 🔹 Overview
Conditional statements are used in C++ to make decisions based on specific conditions. These statements control the flow of execution depending on whether a condition is true or false. The two primary types of conditional statements covered in this experiment are:

1. **If-Else** – A basic conditional control structure that evaluates a condition and executes the relevant block accordingly.
2. **Switch-Case** – A multi-way branching statement that allows the variable to be tested for equality against a list of values.

### 🔸 If-Else Statement
- The `if` statement checks a condition and executes a block of code if it is true.
- The `else` clause executes when the `if` condition is false.
- Can also include multiple `else if` clauses for complex decision chains.

### 🔸 Switch-Case Statement
- Used when a variable is compared against multiple constant values.
- Each `case` acts as a branch.
- A `default` case handles any unmatched condition.
- **Note:** In this implementation, the `switch` statement is used to demonstrate multiple sub-experiments where each `case` performs a different task.

---

## 🧮 Algorithm

### A. If-Else Program – Check Whether a Number is Even or Odd
1. Start
2. Accept a number from the user.
3. If number % 2 == 0, print "Even"
4. Else, print "Odd"
5. End

---

### B. If-Else Program – Find the Largest Among Three Numbers
1. Start
2. Accept three numbers: a, b, and c
3. If a > b and a > c, print "a is the largest"
4. Else if b > c, print "b is the largest"
5. Else, print "c is the largest"
6. End

---

### C. If-Else Program – Check Whether a Character is a Vowel or Consonant
1. Start
2. Accept a character
3. If character is 'a', 'e', 'i', 'o', 'u' (case insensitive), print "Vowel"
4. Else, print "Consonant"
5. End

---

### D. Switch-Case Program – Multi-Function Menu Using Switch (Sub-Experiments as Cases)

#### Main Structure:
1. Start
2. Display a menu with multiple choices to the user
3. Accept user's choice
4. Use `switch(choice)` to execute one of the following cases:

##### 🔹 Case 1: Calculator – Add, Subtract, Multiply, Divide
- Accept two numbers and operation type
- Perform the operation
- Display result

##### 🔹 Case 2: Find Grade Based on Marks
- Accept marks
- Use range conditions to determine grade (A/B/C/Fail)

##### 🔹 Case 3: Simple Interest Calculator
- Accept principal, rate, and time
- Calculate SI = (P × R × T) / 100
- Display result

##### 🔹 Case 4: Check Leap Year
- Accept a year
- If (year % 4 == 0 && year % 100 != 0) || (year % 400 == 0), print "Leap Year"
- Else, print "Not a Leap Year"

##### 🔹 Case 5: Exit
- Terminate the program

5. End

---

## ✅ Conclusion
This experiment demonstrated the practical use of conditional statements in C++. The If-Else construct was effectively used for decision-making based on boolean conditions, while the Switch-Case construct showcased a menu-driven approach with multiple sub-programs as cases. These fundamental constructs are critical for controlling program flow and logic in real-world applications.
