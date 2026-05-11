# Session 1 Tasks – Python Programming

> Practice problems from Session 1 of the **Data Science Mentorship Program by CampusX**.  
> Solve each question on your own to reinforce what you learned in the session.

---

## 📋 Questions Overview

| # | Topic | Concepts |
|---|-------|----------|
| Q1 | String Formatting | `print()` separator & end parameters |
| Q2 | Temperature Conversion | Arithmetic operators, formulas |
| Q3 | Swap Two Numbers | Variable manipulation (no built-in swap) |
| Q4 | Euclidean Distance | Math operations, `input()` |
| Q5 | Simple Interest | Formula-based computation |
| Q6 | Dogs & Chickens Problem | System of equations, logic |
| Q7 | Sum of Squares | Arithmetic series formula |
| Q8 | Nth Term of Arithmetic Series | Sequences & series |
| Q9 | Sum of Two Fractions | Fractions, LCM/GCD logic |
| Q10 | Milk Tank Problem | Volume calculations, geometry |

---

## 🧩 Problem Statements

### Q1 — String Formatting
Print the given strings in a specific format using `sep` and `end` parameters of `print()`.

**Input strings:**
```
"Data" "Science" "Mentorship" "Program"
"By" "CampusX"
```
**Expected Output:**
```
Data-Science-Mentorship-Program-started-By-CampusX
```

---

### Q2 — Celsius to Fahrenheit
Write a program that converts a Celsius temperature value to Fahrenheit.

**Formula:**
```
F = (C × 9/5) + 32
```

---

### Q3 — Swap Two Numbers
Take 2 numbers as input from the user and swap them **without using any special Python syntax** (i.e., no tuple unpacking like `a, b = b, a`).

---

### Q4 — Euclidean Distance
Write a program to find the Euclidean distance between two 2D coordinates provided by the user.

**Formula:**
```
distance = √((x2 - x1)² + (y2 - y1)²)
```

---

### Q5 — Simple Interest
Calculate simple interest given the principal, rate of interest, and time period (all provided by the user).

**Formula:**
```
SI = (P × R × T) / 100
```

---

### Q6 — Dogs and Chickens
Given the total number of **heads** and **legs**, determine how many dogs and chickens there are.

**Example:**
```
Input:  heads = 4, legs = 12
Output: dogs = 2, chickens = 2
```

**Hint:** Dogs have 4 legs, chickens have 2.

---

### Q7 — Sum of Squares of First N Natural Numbers
Find the sum of squares of the first `n` natural numbers, where `n` is provided by the user.

**Formula:**
```
Sum = n × (n + 1) × (2n + 1) / 6
```

---

### Q8 — Nth Term of an Arithmetic Series
Given the first two terms of an arithmetic series, find the Nth term. All inputs are provided by the user.

**Formula:**
```
Nth term = a + (n - 1) × d
where d = term2 - term1
```

---

### Q9 — Sum of Two Fractions
Take the numerators and denominators of two fractions from the user and find their sum.

**Formula:**
```
a/b + c/d = (a×d + b×c) / (b×d)
```
Simplify the result using GCD.

---

### Q10 — Milk Tank Problem
Given the dimensions of a rectangular milk tank and a cylindrical glass, find how many glasses of milk can be filled from the tank.

**Given (example):**
- Tank: H = 20 cm, L = 20 cm, B = 20 cm
- Glass: h = 3 cm, r = 1 cm

**Formulas:**
```
Volume of tank  = H × L × B
Volume of glass = π × r² × h
Number of glasses = Volume of tank / Volume of glass
```

---

## 🚀 How to Use

1. Open `session_1_tasks.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Write your solution in each cell marked `# Write your code here`.
3. Run the cells to verify your output.

---

## 🛠️ Requirements

- Python 3.x
- No external libraries required (only the built-in `math` module for some questions)

---

## 📚 Key Concepts Covered

- `print()` with `sep` and `end` parameters
- Arithmetic operators and expressions
- Taking user input with `input()` and type casting
- Basic math formulas and their Python implementation
- Problem decomposition using systems of equations

---

*Happy Learning! 🎉*
