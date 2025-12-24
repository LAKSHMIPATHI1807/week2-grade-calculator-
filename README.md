# Student Grade Calculator

## Project – Student Grade Calculator

## Project Description

A comprehensive grade calculator that processes multiple students' marks, calculates grades with personalized comments, and provides class statistics such as class average, highest score, and lowest score.

---

## ⚙️ Setup and Installation Instructions

### 1. Install Python

* Download Python from: [https://www.python.org](https://www.python.org)
* During installation:

  * Check **“Add Python 3.x to PATH”**
  * Click **Install**

### 2. Verify Installation

* Open **Command Prompt**
* Run:

  ```bash
  python --version
  ```

### 3. Set Up VS Code

* Open **Visual Studio Code**
* Go to **Extensions**
* Search for **Python**
* Install **Python (by Microsoft)**

---

## 🛠️ Project Technical Requirements

This project meets the following technical requirements:

* Uses `if / elif / else` statements for grade calculation
* Implements **lists** to store multiple students’ data
* Uses **for loops** to process all students
* Uses **while loops** for input validation
* Implements **try-except** blocks for error handling
* Calculates statistics:

  * Average
  * Highest score
  * Lowest score
* Provides personalized comments based on grades
* Displays results in a formatted table

---

## 📂 Code Structure

```
week2-grade-calculator/
│── grade_calculator.py
│── test_students.txt
│── results_sample.txt
│── README.md
└── .gitignore
```

---

## 🧠 Program Logic Overview

### Grade Calculation

Grades are assigned based on average marks:

* **A** → Excellent!
* **B** → Very good!
* **C** → Good!
* **D** → Needs Improvement!
* **F** → Fail!

### Input Validation

* Ensures marks are between **0 and 100**
* Prevents empty student names
* Handles invalid input using `try-except`

### Data Storage

* Student names, marks, and results are stored using lists and dictionaries.

---
## Output
The program displays:

* Student name
* Average marks
* Grade
* Comment
* Class statistics:

  * Total students
  * Class average
  * Highest and lowest average scores
---
## Test Cases

### Case 1: Input Validation

* If the user enters invalid input (empty name or non-numeric marks), the program displays an error message.
* Execution continues only after valid input is provided.

### Case 2: Successful Execution

* When valid inputs are provided, the program executes successfully.
* All students’ grades and statistics are calculated and displayed correctly.
---

## How to Run the Program

```bash
python grade_calculator.py
```

(Optional)

```bash
python grade_calculator.py < test_students.txt
```
## Conclusion

This project successfully demonstrates the use of Python control structures, data storage, error handling, and formatted output to build a complete student grade calculator.
