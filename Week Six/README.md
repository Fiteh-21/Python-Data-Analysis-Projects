
# ☕ Cozy Bean Performance & Weather Impact Analysis

## 📊 Python for Data Analysis | Week 6 Project

An executive visual data analysis project focused on translating numerical retail summaries into impactful, presentation-ready data stories. This repository leverages Python (`pandas`, `matplotlib`, and `seaborn`) to uncover operational insights and guide strategic decision-making for the Cozy Bean coffee shop chain.

## 📊 Business Objectives
The analysis seeks to evaluate daily performance variations across diverse store profiles by answering three foundational retail operations questions:
1. **Trend Identification**: What do daily revenue patterns look like across the operational month?
2. **Operational Dependencies**: Does weather affect customer behavior equally across different store locations?
3. **Distribution Analysis**: How do volume variance and top-performing days differ between store footprints?

## 🛠️ Data Visualization Principles Applied
Following professional analytics industry practices taught in our core visualization workshop, every chart in this repository strictly adheres to a rigorous design philosophy:

* **The 4-Line Matplotlib Pattern**: Clean, explicit object-oriented instantiation (`fig, ax = plt.subplots()`) ensuring reproducible layouts and tight control over figure rendering.
* **Strategic Storytelling Design Moves**:
  * **Declutter**: Suppressed unnecessary chart clutter, boundaries, excessive grids, and redundant axis labels to dramatically improve the data-to-ink ratio.
  * **Cognitive Accent Coloration (Highlight)**: Kept charts grounded in neutral, muted base tones (such as greys) to minimize cognitive load, reserving a single, strategic accent color to draw the user's eye directly to the primary analytical insight.
  * **Takeaway Headlining**: Replaced traditional, generic titles (e.g., *"Revenue vs. Weather Column Plot"*) with action-oriented headers summarizing the explicit takeaway of the graphic.
* **Production-Grade Exports**: Cleanly saved all final figures to high-resolution PNG format (`dpi=150`) optimizing them for corporate slide decks and executive briefings.

---


## 📈 Featured Visual Insights

### 1. Multi-Panel Subplot Layout (`sns.catplot`)

Answering the challenge: *"Does weather affect each store equally?"* This visual separates performance indicators by location footprint inside a clean, column-wrapped Seaborn multi-panel grid system.

It highlights that while outdoor or standalone foot-traffic hubs experience sudden rain-day dips, the enclosed indoor mall store remains entirely insulated from environmental changes.

### 2. Targeted Categorical Distribution

Using a minimalist boxplot configuration accented with targeted color fills to draw immediate attention to high-revenue variance profiles, showing stakeholders exactly where performance volatility sits.

---

## 🎓 Key Technical Competencies Demonstrated

* **Toolchain Fluidity**: Seamlessly balancing Matplotlib's precise figure controls with Seaborn's shorter syntax, smart defaults, and advanced grid structures.
* **Problem-First Plot Selection**: Selecting data chart structures exclusively based on the question being asked, rather than hunting for a question to fit a pre-conceived graphic style.
* **Executive Presentation Styling**: Turning raw, default python graphics into clean, story-driven communication assets ready for cross-functional stakeholders.
