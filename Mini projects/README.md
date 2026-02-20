# 🧮 Advanced Calculator — Python (Google Colab)

> An interactive, menu-driven **Advanced Calculator** built in Python using Object-Oriented Programming (OOP). Covers arithmetic operations, statistical analysis, and a multi-mode percentage calculator — all from a clean class-based design.

---

## 📌 Project Overview

This project was built and run in **Google Colab** as a hands-on Python exercise. It demonstrates core programming concepts like classes, methods, type casting, input validation, loops, and error handling — packaged into a fully functional CLI calculator.

---

## ✨ Features

| Feature | Description |
|---|---|
| ➕ **Addition** | Sum of two numbers |
| ➖ **Subtraction** | Difference of two numbers |
| ✖️ **Multiplication** | Product of two numbers |
| ➗ **Division** | Quotient with divide-by-zero protection |
| 📊 **Modulus** | Remainder with zero-divisor guard |
| 📈 **Statistics** | Mean, Median, Mode, Range, Count, Sum for a list of numbers |
| 📊 **Percentage Calculator** | Three percentage modes (see below) |
| 🔁 **Interactive Loop** | Menu-driven — runs until user exits |

---

## 📊 Statistical Analysis (Option 6)

Accepts any list of space-separated numbers and outputs:

- **Mean** (arithmetic average)
- **Median** (middle value, handles even/odd length lists)
- **Mode** (most frequent value, handles multi-mode and no-mode cases)
- **Range** (max − min)
- **Count** (total numbers entered)
- **Sum** (total)

**Example run:**
```
Numbers: 45 76 54 32 11 90

📊 Statistical Analysis for: [45, 76, 54, 32, 11, 90]
📈 Mean (Average): 51.33
📊 Median: 49.5
🎯 Mode: No mode (all values appear equally)
📏 Range: 79
🔢 Count: 6
📊 Sum: 308
```

---

## 📐 Percentage Calculator (Option 7)

Three sub-modes:
1. **What is X% of Y?** — e.g., 20% of 500 = 100
2. **X is what % of Y?** — e.g., 75 is 25% of 300
3. **X% more or less than Y?** — e.g., 10% more than 200 = 220

---

## 🏗️ Code Structure

```
Calculator (class)
│
├── get_number_input()       # Smart input with int/float type casting + validation
├── get_numbers_list()       # Parses space-separated number input for stats
│
├── addition()               # a + b
├── subtraction()            # a - b
├── multiplication()         # a × b
├── division()               # a ÷ b (zero-check)
├── modulus()                # a % b (zero-check)
│
├── calculate_mean()         # sum / count
├── calculate_median()       # handles odd & even length lists
├── calculate_mode()         # uses Counter, handles multi-mode / no-mode
├── statistics_menu()        # orchestrates all stats and displays results
│
├── percentage_calculator()  # 3-mode percentage logic
├── display_menu()           # prints the main menu
└── run()                    # main loop with try/except + KeyboardInterrupt handler
```

---

## 🐍 Python Concepts Used

- **OOP** — single `Calculator` class with methods for each operation
- **Type Casting** — intelligently casts input to `int` or `float` based on presence of `.`
- **Type Hints** — `List`, `Union`, `float` from `typing` module
- **`collections.Counter`** — used for efficient mode calculation
- **`math`** module — imported for potential extension
- **Error Handling** — `try/except ValueError` and `KeyboardInterrupt` throughout
- **f-strings** — clean, readable formatted output
- **`while True` loop** — keeps the app running until user selects Exit

---

## 🚀 How to Run

### ▶️ Option 1 — Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `calculator.ipynb`
3. Run the cell — the interactive menu will appear in the output

### 💻 Option 2 — Local (Jupyter Notebook)
```bash
pip install notebook
jupyter notebook calculator.ipynb
```

### 🖥️ Option 3 — Convert to Python Script
```bash
jupyter nbconvert --to script calculator.ipynb
python calculator.py
```

---

## 🧾 Sample Session

```
🧮 Advanced Calculator
==================================================

🧮 Calculator Menu
==============================
1. ➕ Addition
2. ➖ Subtraction
3. ✖️  Multiplication
4. ➗ Division
5. 📊 Modulus (%)
6. 📈 Statistics (Mean, Median, Mode, Average)
7. 📊 Percentage Calculator
8. ❌ Exit
------------------------------
Enter your choice (1-8): 1
Enter first number: 21
Enter second number: 54
✅ 21 + 54 = 75
```

---

## 📁 File Structure

```
📦 advanced-calculator/
 ┗ 📓 calculator.ipynb    # Main Jupyter Notebook (Colab-ready)
 ┗ 📄 README.md           # Project documentation
```

---

## 🛠️ Requirements

- Python 3.x
- Standard library only — no external packages needed (`math`, `collections`, `typing`)

---

## 🎯 Learning Outcomes

- Designing a program using **Object-Oriented Programming**
- Implementing **robust input validation** with loops and exceptions
- Building **statistical functions from scratch** (mean, median, mode)
- Structuring an **interactive CLI application** in Python
- Writing clean, readable, well-commented code

---

*Built with Python · Runs on Google Colab · No external dependencies*
