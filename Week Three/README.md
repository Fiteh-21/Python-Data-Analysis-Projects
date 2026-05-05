# Cozy Bean Coffee Shop: Pandas Fundamentals Workshop

## 📊 Python for Data Analysis | Week 3 Project

This project serves as a comprehensive guide to mastering the fundamentals of the **pandas** library in Python. Using a practical business case analyzing sales data for the Cozy Bean Coffee Shop this workshop demonstrates how to manipulate, filter, and inspect data effectively.

---

## ☕ Project Overview
The analysis focuses on a dataset containing sales records across four different coffee shop locations. The project covers the transition from basic data structures to advanced data cleaning and business logic.

### Key Data Features:
*   **Store Locations**: Downtown, Airport, Mall, and Suburb.
*   **Metrics**: Drinks sold, total revenue, and daily weather conditions.
*   **Temporal Data**: Date-based records including days of the week.

---

## 🛠️ Workshop Sections

### 1. Data Structures & Loading
*   **Series vs. DataFrames**: Understanding the difference between 1D arrays and 2D labeled structures.
*   **Data Ingestion**: Loading data from CSV files using `pd.read_csv()`.

### 2. Data Inspection
*   **Shape & Metadata**: Using `.shape` and `.info()` to understand dataset dimensions and data types.
*   **Statistical Analysis**: Utilizing `.describe()` to calculate mean, standard deviation, and quartiles for sales and revenue.

### 3. Selection Techniques
*   **Label-based Selection (`.loc`)**: Selecting data by index labels and column names (inclusive).
*   **Position-based Selection (`.iloc`)**: Selecting data by integer positions (exclusive of the final index).

### 4. Advanced Filtering & Boolean Masking
*   **Conditional Logic**: Filtering rows based on specific criteria (e.g., `drinks_sold > 200`).
*   **Complex Queries**: Combining multiple conditions using bitwise operators (`&`, `|`) to find specific scenarios, such as "Sunny days at the Mall location".
*   **List Filtering**: Using `.isin()` to filter for specific categories like weekend sales.

### 5. Sorting and Insights
*   **Performance Ranking**: Using `.sort_values()` to identify the highest revenue days and top-performing stores.

---

## 🚀 How to Use
1.  **Clone the Repository**: Download the project files to your local machine.
2.  **Run the Setup**: The first cell in the Jupyter Notebook generates the `cozy_bean_sales.csv` file automatically.
3.  **Execute the Cells**: Follow along with the markdown explanations and code blocks to learn pandas interactively.

---

## 📋 Requirements
*   Python 3.x
*   pandas
*   numpy
*   Jupyter Notebook or VS Code (with Jupyter extension)