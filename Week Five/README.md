# Cozy Bean — Retail Operations & Analytics Dashboard

## 📊 Project Overview

This project serves as an executive-level Exploratory Data Analysis (EDA) dashboard engineered around the multi-unit operations of **Cozy Bean Coffee**. The analysis moves from raw operational logs across four distinct commercial footprints (Airport, Mall, Suburb, and City Center) into high-dimensional grouping, multi-variable data reshaping, and vectorized statistical auditing.

Instead of running disconnected functions, this project demonstrates a structured data science workflow turning noisy row-level logs into concrete, actionable business intelligence.

## 🎯 Key Learning Objectives & Core Skills (Week 5 Milestone)

This repository showcases absolute proficiency in the foundational data manipulation patterns learned during **Week 5**:

- **High-Dimensional Summarization:** Auditing baseline categorical densities and numeric ranges before slicing parameters.
- **Advanced Grouping & Named Aggregations:** Slicing metrics across multiple variables concurrently while keeping flat structural clarity.
- **Structural Reshaping:** Utilizing Wide-to-Long (`melt`) and Long-to-Wide (`pivot_table`) conversions to format tables for reporting engines vs. downstream machine learning/plotting pipelines.
- **Vectorized Window Operations:** Leveraging pandas `.transform()` to broadcast grouped dataset benchmarks across individual log rows without slow python loops.

---

## 🛠️ Operational Challenges Resolved

The analysis explicitly provides answers to the core end-of-week analytical challenges:

1.  **Socio-Environmental Drivers:** Isolated the exact combination of `weekday` and `weather` that yields the highest average gross daily revenue.
2.  **Portfolio Volume Contributions:** Computed each individual store's exact market share percentage out of total monthly gross system revenue.
3.  **Statistical Outlier Auditing:** Built a dynamic statistical monitoring system using the $Mean + 2\sigma$ (Standard Deviation) rule via `.transform()` to flag outlier operations.

---

## 📂 Repository Structure

```text
├── cozy.ipynb   # Main Jupyter Notebook with code & analysis
└── README.md                        # Project documentation and executive overview

```

---

## 💻 Key Insights & Dashboard Preview

When executed, the system consolidates raw daily telemetry into an automated operational terminal dashboard:

- **Dominant Performance Footprint:** The Mall location (**Store C**) serves as the core revenue anchor, driving the largest volume share.
- **Anomaly Registration:** The dynamic outlier threshold successfully isolated operational anomalies that fall outside normal random variations—allowing managers to pinpoint critical spikes in demand.
- **Format Flexibility:** Transformed human-readable pivot summaries back into data-pipeline friendly structures using `.melt()`, proving a solid understanding of tidy data standards.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have `pandas` and `numpy` installed in your Python environment:

```bash
pip install pandas numpy

```

### Execution

1. Clone this repository to your local machine.
2. Open your terminal and start Jupyter Notebook:

```bash
jupyter notebook

```

3. Run `cozy.ipynb` cell-by-cell to view the analysis step-by-step or check the final printed terminal report.

---
