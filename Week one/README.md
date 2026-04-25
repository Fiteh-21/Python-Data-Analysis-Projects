# 💰 SpendWise - Minimalist Personal Finance Tracker

## 📊 Python for Data Analysis | Week 1 Project

SpendWise is a Python-based personal finance tracker built as part of my Data Analysis learning journey (Week 1 milestone). This project demonstrates how core Python concepts can be applied to model, process, and analyze financial data in a structured and meaningful way.

### 📌 Project Overview

This project analyzes a dataset of monthly transactions using Python. It categorizes expenses, calculates totals, compares spending against a predefined budget, and generates a clear financial report.

The goal is to simulate a simple real-world data analysis workflow using only foundational Python skills.

### 🎯 Key Features

- 📂 Structured dataset using lists of dictionaries
- 🧮 Total expense calculation
- 📊 Budget comparison with status indicators
- 🔍 Breakdown of Fixed vs Variable expenses
- 📄 Clean, formatted financial report output
- 🧾 Detailed transaction log

### 🛠️ Technologies Used

- Python (Core concepts only)
  - Lists & Dictionaries
  - Functions
  - Loops & Conditionals
  - F-Strings for formatting

### 📁 Project Structure

```
spendwise/
│
├── SpendWise.ipynb     # Main project notebook
├── README.md           # Project documentation
```

### 📊 Dataset Description

The dataset consists of a list of transaction records, where each transaction includes:

- Date
- Category (e.g., Rent, Groceries, Transport)
- Amount
- Type (Fixed or Variable)

Example:

```bash
{
  "date": "2026-04-01",
  "category": "Rent",
  "amount": 1200.00,
  "type": "Fixed"
}
```

### ⚙️ How It Works

1. Data Initialization

   A clean dataset of transactions is defined along with a monthly budget.

2. Analysis Functions

   Custom functions are used to:
   - Calculate total spending
   - Evaluate budget status
   - Summarize expenses by type

3. Report Generation

   A reporting function compiles all insights and prints a structured financial summary, including:
   - Total spending
   - Budget comparison
   - Expense breakdown
   - Detailed transaction log

### 📈 Sample Output

```
==================================================
           SPENDWISE FINANCIAL REPORT
==================================================
Total Transactions: 8
Total Monthly Spent: $1,647.44
Monthly Budget:      $2,000.00
Financial Status:    ✅ WITHIN BUDGET
--------------------------------------------------
SPENDING BREAKDOWN BY TYPE:
- Fixed   : $1,325.99 (80.5%)
- Variable: $321.45 (19.5%)
--------------------------------------------------
```

### 🧠 What I Learned

- Structuring real-world data using Python
- Writing reusable and modular functions
- Performing basic data analysis without external libraries
- Presenting insights in a clear, readable format
- Building a complete mini-project from scratch
