# 📊 Data Analytics Learning Journey

My hands-on practice repository for building job-ready **data analytics** skills, starting with Python fundamentals and moving through NumPy, Pandas, SQL, Advanced Excel & DAX, and Power BI.

Each section below is one assignment or project. Every section lists what was practiced and what it builds toward.

## 📑 Table of Contents

1. [Strings and Tuples](#1-strings-and-tuples)
2. [Lists, Dictionaries, and Sets](#2-lists-dictionaries-and-sets)
3. [While Loop, For Loop & Functions](#3-while-loop-for-loop--functions)
4. [Survey Feedback Analyzer](#4-survey-feedback-analyzer)
5. [Data Analysis using NumPy and Pandas](#5-data-analysis-using-numpy-and-pandas)

---

## 1. Strings and Tuples
📓 **Notebook:** [`Data_Structures-Strings_&_Tuples.ipynb`](./Data_Structures-Strings_&_Tuples)
This assignment covers two fundamental Python sequence types: **strings** and **tuples**. It builds a foundation for accessing and manipulating sequence elements.

### Concepts Covered

* **Strings:** concatenation, indexing, slicing
* **String methods:** `upper()`, `lower()`, `capitalize()`, `count()`, `replace()`
* **Tuples:** creation, concatenation, repetition, indexing, slicing

---

## 2. Lists, Dictionaries, and Sets

This assignment covers the core Python collections along with **conditional statements**.

### Concepts Covered

* **Lists:** creating, accessing, and modifying with `append()`, `insert()`, `remove()`, `pop()`, `extend()`, `sort()`
* **List indexing and slicing**
* **Dictionaries:** key-value pairs
* **Sets:** union and intersection
* **Conditionals:** `if`, `elif`, `else`

### Mini Program: Performance Category

Takes a score from the user and reports whether performance is **Above Average**, **Average**, or **Below Average**.

---

## 3. While Loop, For Loop & Functions

Practice with **loops, control statements, and functions** through simple real-world problems, focused on logical thinking, iteration, user input, and reusable code.

### 3.1 While Loop & Control Statements: Number Guessing Game

A random number between 1 and 10 is generated and the user gets a limited number of attempts. The program gives feedback for guesses that are too high, too low, or outside the valid range.

**Concepts:** `while` loop, `if` / `elif` / `else`, `break`, `continue`, `while...else`, `random.randint()`, user input, counters and conditions

### 3.2 For Loop: Multiplication Table Generator

The user enters a number and the program prints its multiplication table from 1 to 10.

**Concepts:** `for` loop, `range()`, iteration, arithmetic operations, user input, output formatting

### 3.3 Functions: BMI Calculator

A `calculate_bmi(weight, height)` function computes Body Mass Index and returns the result for display.

**Concepts:** `def`, parameters and arguments, function calling, `return`, `float()`, `round()`

### Key Learning

* `while` loops for condition-based repetition and `for` loops for sequence-based iteration
* How `break`, `continue`, and `else` change loop flow
* Writing reusable functions that take parameters and return values
* Converting user input and formatting numeric output

---

## 4. Survey Feedback Analyzer

A Python project that analyzes customer survey feedback using core Python fundamentals.

### 🎯 Concepts Used

* Dictionaries & lists
* `for` loops & `if` conditions
* Functions
* User input
* String methods: `.replace()`, `.split()`, `.join()`, `.lower()`
* Sets
* `sum()` & `len()`
* `zip()` & `sorted()`

### 🎯 Objectives

* Store structured survey data using dictionaries and lists
* Add new feedback entries using user input
* Clean text data using string methods
* Create and use user-defined functions
* Count specific words across feedback
* Calculate the average rating
* Find the longest feedback comment
* Identify unique words using sets
* Sort feedback based on ratings

### 🔄 What the Project Does

* Stores survey feedback and ratings
* Adds new feedback through user input
* Cleans feedback text
* Counts words like **good**, **poor**, and **excellent**
* Calculates the average rating
* Finds the longest feedback
* Identifies unique words
* Sorts feedback by rating

### 🧠 Key Learning

This project applies Python fundamentals to a practical **data cleaning and analysis** problem, building a foundation for **NumPy, Pandas, EDA, and data visualization**.

**Skills:** Python Fundamentals | Data Cleaning | String Manipulation | Data Analysis

---

## 5. Data Analysis using NumPy and Pandas

A hands-on notebook that moves from core Python into the two libraries every data analyst uses daily: **NumPy** for numerical arrays and **Pandas** for tabular data.

📓 **Notebook:** [`Data_Analysis_using_NumPy_and_Pandas.ipynb`](./Data_Analysis_using_NumPy_and_Pandas.ipynb)

### 🎯 Concepts Used

* NumPy 1D and 2D arrays
* Array properties: `.shape`, `.dtype`, `.size`
* Vectorized arithmetic and aggregation: `np.max()`, `np.min()`, `np.mean()`
* Array indexing and slicing
* Pandas `Series` with custom indexes
* Label-based vs position-based access: `.loc[]` and `.iloc[]`
* Boolean filtering
* Pandas `DataFrame` creation and exploration
* `groupby()`, `value_counts()`, `unique()`
* `apply()` with user-defined functions
* Adding, updating, and dropping rows and columns

### 📂 Notebook Structure

#### NumPy Array Operations

| Step | What I Practiced |
|------|------------------|
| Create a 1D array | Weekly temperature readings stored with `np.array()` |
| Inspect properties | `shape`, `dtype`, `size` |
| Array operations | Vectorized temperature conversion, plus max, min, and mean |
| Slicing and indexing | `[:3]`, `[5:]`, `[3:6]` |
| Create a 2D array | Two weeks of temperature data as a 2 × 7 matrix |
| Inspect and slice 2D | Row and column access such as `temperatures[0, -2:]` |

#### Pandas Series

| Step | What I Practiced |
|------|------------------|
| Create a Series | Marks indexed by rank labels |
| Indexing and slicing | `.iloc[]` (by position), `.loc[]` (by label), boolean filter `marks > 90` |
| Manipulating | Updating a value, `drop()`, and element-wise math (marks → CGPA) |

#### Pandas DataFrame

A 10-row **retail transactions** dataset with `TransactionID`, `ProductCategory`, `Region`, and `Amount`.

| Step | What I Practiced |
|------|------------------|
| Create a DataFrame | Building a DataFrame from a dictionary of lists |
| Data exploration | `info()`, `head()`, `tail()`, `shape`, `columns`, `dtypes` |
| Selecting data | Column subsets, `iloc` row slicing, multi-condition filtering with `&` |
| Summarizing | `value_counts()`, `unique()`, `groupby("Region")["Amount"].mean()` |
| Manipulating | Conditional update with `.loc[]`, new column via `apply()`, `drop()` on rows (`axis=0`) and columns (`axis=1`) |

### 🔄 What the Notebook Does

* Stores and inspects numerical data using NumPy arrays
* Applies calculations to a whole array at once without loops
* Slices 1D and 2D arrays to extract specific readings
* Builds labeled Series and filters them with conditions
* Builds a structured transactions DataFrame from a dictionary
* Filters transactions by region and amount
* Calculates average sales amount per region
* Creates a derived column and removes unwanted rows and columns

### 🧠 Key Learning

* **NumPy** is built for fast, vectorized math on uniform numeric data, so a single expression replaces a loop.
* **Pandas** adds labels and mixed column types, which makes it the right tool for real-world business data.
* `.loc[]` selects by label and `.iloc[]` selects by position. Mixing them up is one of the most common beginner bugs.
* Combining filters needs `&` / `|` with parentheses around each condition, not `and` / `or`.
* `groupby()` is the Pandas equivalent of SQL's `GROUP BY` and is the foundation of most analysis work.
* `drop()` returns a new object unless `inplace=True` is used.

**Skills:** NumPy | Pandas | Data Exploration | Filtering & Grouping | Data Manipulation

---



## 🛠️ Tech Stack

Python | NumPy | Pandas | Jupyter Notebook
