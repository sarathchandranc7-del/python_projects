# 📊 Data Analytics Learning Journey

My hands-on practice repository for building job-ready **data analytics** skills, starting with Python fundamentals and moving through NumPy, Pandas, SQL, Advanced Excel & DAX, and Power BI.

Each section below is one assignment or project. Every section lists what was practiced and what it builds toward.

## 📑 Table of Contents

1. [Strings and Tuples](#1-strings-and-tuples)
2. [Lists, Dictionaries, and Sets](#2-lists-dictionaries-and-sets)
3. [While Loop, For Loop & Functions](#3-while-loop-for-loop--functions)
4. [Survey Feedback Analyzer](#4-survey-feedback-analyzer)
5. [Data Analysis using NumPy and Pandas](#5-data-analysis-using-numpy-and-pandas)
6. [Taxi_Data_Visualisation](#6-Taxi-Data-Visualisation)

---

## 1. Strings and Tuples
📓 **Notebook:** [`Data_Structures-Strings_&_Tuples`](./Data_Structures-Strings_&_Tuples.ipynb)
This assignment covers two fundamental Python sequence types: **strings** and **tuples**. It builds a foundation for accessing and manipulating sequence elements.

### Concepts Covered

* **Strings:** concatenation, indexing, slicing
* **String methods:** `upper()`, `lower()`, `capitalize()`, `count()`, `replace()`
* **Tuples:** creation, concatenation, repetition, indexing, slicing

---

## 2. Lists, Dictionaries, and Sets
📓 **Notebook:** [`Data_Structures-List,Dictionary,Set_&_Conditional_Statements`](./Data_Structures-List,Dictionary,Set_&_Conditional_Statements.ipynb)
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
📓 **Notebook:** [`While_Loop,For_loop_and_Functions`](./While_Loop,For_loop_and_Functions.ipynb)
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
📓 **Notebook:** [`Python_Fundamentals-Survey_Feedback_Analyzer`](./Python_Fundamentals-Survey_Feedback_Analyzer.ipynb)
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

📓 **Notebook:** [`Taxi_Data_Visualisation`](./Taxi_Data_Visualisation.ipynb)

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
## 6. 🚕 Taxi Data Analysis & Visualization Using Python
📓 **Notebook:** [`Taxi_Data_Visualisation`](./Taxi_Data_Visualisation.ipynb)
## 📌 Project Overview

This project focuses on **data cleaning, exploratory data analysis (EDA), and data visualization** using Python.

Using the built-in Taxis dataset from Seaborn, this project explores taxi trip information, including fares, distances, tips, payment methods, pickup boroughs, and other numerical variables.

The objective is to transform raw data into meaningful visualizations that help identify patterns, understand distributions, and explore relationships between variables.

## 🎯 Project Objectives

* Load and explore the Taxis dataset using Python.
* Identify and handle missing values using appropriate imputation strategies.
* Prepare data for analysis and visualization.
* Analyze taxi fares across different pickup boroughs.
* Explore trip distributions across payment methods.
* Visualize the relationship between distance and fare.
* Examine correlations between numerical variables.
* Compare fare and tip distributions across different categories.
* Practice using Matplotlib, Pandas plotting, and Seaborn.

## 🛠️ Technologies & Libraries

| Technology       | Purpose                            |
| ---------------- | ---------------------------------- |
| Python           | Data analysis and programming      |
| Pandas           | Data manipulation and cleaning     |
| Matplotlib       | Creating charts and visualizations |
| Seaborn          | Statistical data visualization     |
| NumPy            | Numerical operations               |
| Jupyter Notebook | Interactive coding and analysis    |

## 📂 Dataset Information

**Dataset:** Taxis Dataset

**Source:** Built-in Seaborn dataset, loaded using `sns.load_dataset("taxis")`.

The dataset contains information about taxi trips, including:

* Pickup and drop-off timestamps
* Pickup and drop-off locations
* Trip distance
* Fare amount
* Tip amount
* Tolls
* Total trip cost
* Payment method
* Pickup borough

These attributes allow us to explore trip characteristics, fare distributions, and relationships between different variables.

## 🔍 Project Workflow

### 1. Loading the Dataset

* Imported the required Python libraries.
* Loaded the Taxis dataset using Seaborn.
* Inspected the dataset and its dimensions.
* Checked for duplicate records.

### 2. Handling Missing Values

* Identified missing values in the dataset.
* Examined missing-value counts across columns.
* Applied suitable imputation strategies based on column types.
* Used mode-based imputation for categorical data where appropriate.
* Addressed missing values in critical columns to maintain data integrity.

### 3. Data Visualization Using Matplotlib and Pandas

#### 📈 Line Chart — Fare Over Time

Visualized fare amounts against pickup timestamps to examine changes in fares over time.

#### 📊 Bar Chart — Total Fare by Pickup Borough

Grouped trips by pickup borough and calculated the total fare for each borough to compare their contributions.

#### 🥧 Pie Chart — Trip Distribution by Payment Method

Displayed the distribution of trips across payment methods, such as credit card and cash.

#### 📉 Histogram — Distance Distribution

Visualized the distribution of trip distances using customizable bins to understand how trip lengths are distributed.

#### 📦 Box Plot — Tip Distribution by Pickup Borough

Compared tip amounts across pickup boroughs to examine differences in distributions and identify potential outliers.

### 4. Data Visualization Using Seaborn

#### 📊 Count Plot — Trips by Pickup Borough

Compared the number of trips recorded for each pickup borough.

#### 🔵 Scatter Plot — Distance vs. Fare

Explored the relationship between trip distance and fare, using pickup borough to distinguish observations.

#### 🔥 Heatmap — Correlation Between Numerical Variables

Visualized correlations between numerical variables, including distance, fare, tip, tolls, and total trip cost.

#### 🔗 Pair Plot — Relationships Between Numerical Variables

Explored pairwise relationships between distance, fare, tip, and total trip cost, with pickup zone used to distinguish categories.

#### 🎻 Violin Plot — Fare Distribution by Payment Method

Compared fare distributions across payment methods to examine their spread, density, and variation.

## 📊 Key Analysis Areas

This project explores the following analytical questions:

* How does the fare vary over time?
* Which pickup borough contributes the highest total fare?
* Which payment methods are used for taxi trips?
* What does the distribution of trip distances look like?
* How do tip amounts vary across pickup boroughs?
* How many trips originate from each borough?
* Is there a relationship between distance and fare?
* How strongly are fare, distance, tips, tolls, and total cost correlated?
* How do numerical variables relate to one another?
* How does fare distribution differ across payment methods?

## 💡 Skills Demonstrated

* Python programming
* Data cleaning and missing-value handling
* Exploratory data analysis (EDA)
* Data aggregation and grouping
* Statistical visualization
* Categorical and numerical data analysis
* Correlation analysis
* Data interpretation
* Analytical thinking

## 🏁 Conclusion

This project demonstrates how Python can be used to clean, explore, and visualize real-world-style taxi trip data.

By combining Matplotlib, Pandas, and Seaborn, the analysis examines fare patterns, trip distributions, borough-level comparisons, and relationships between numerical variables.

The project provides practical experience in the data preparation and visualization stages of a typical data analytics workflow.

---

**Project Category:** Data Analytics | Exploratory Data Analysis | Data Visualization

**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook



## 🛠️ Tech Stack

Python | NumPy | Pandas | Jupyter Notebook
