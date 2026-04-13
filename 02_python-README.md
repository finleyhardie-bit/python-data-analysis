# Python Data Analysis

**Finley Hardie — INFO 3100: Automating Business Processes with Python**

Python-based data analysis work from INFO 3100 at the University of Denver. Projects cover data merging, exploratory analysis, groupby summaries, pivot tables, and statistical investigation — using real (and realistic) datasets.

---

## Projects

### NBA Player Performance Analysis (`INFO3100_Python_Project.ipynb`)
The main project for the course. Analyzes a dataset of 50 NBA players from the 2023–24 season, investigating three research questions:

- **RQ1:** Do players in different positions (PG, SG, SF, PF, C) differ in average points per game?
- **RQ2:** Is there a positive relationship between minutes played and points scored?
- **RQ3:** Do Eastern and Western Conference players differ in average assists?

Key findings: PGs scored the most per game on average (18.77); minutes and scoring were strongly correlated (r = 0.64); conference had virtually no effect on assists (East: 4.29, West: 4.28).

**Techniques:** data merging, descriptive statistics, groupby analysis, Pearson correlation, crosstabulation

---

### Ice Cream Sales Data Wrangling (`ABPPY5MiniAssignment_Completed.ipynb`)
A structured data manipulation exercise using retail ice cream sales data across three Colorado stores (Denver, Greeley, Parker).

- Loaded, concatenated, and merged three CSV files into a single clean DataFrame
- Grouped by flavor, store, and customer type to surface sales patterns
- Built a reusable `column_summaries()` function that takes a DataFrame and returns either numerical or categorical summaries on demand
- Created pivot tables showing transaction counts by store and customer segment

**Techniques:** `pd.concat`, `pd.merge`, `groupby`, `pivot_table`, custom functions

---

### Supporting Assignments
A progression of shorter exercises building toward the main project:

| File | Focus |
|------|-------|
| `MINI_ASSIGNMENT2.ipynb` | DataFrame creation, filtering, and basic operations |
| `MINIASSIGNMENT3.ipynb` | Loops, conditionals, and list comprehensions applied to data |
| `Hardie_Mini_Assignment_4.ipynb` | Functions and structured data processing |
| `ABPPY4MiniAssignment.ipynb` | File I/O and data cleaning |
| `PYTHON L1 Mini Assignment.ipynb` | Python fundamentals: variables, types, basic syntax |

---

## Data Files

| File | Description |
|------|-------------|
| `IceCreamData.csv` | Original 37-row retail sales dataset |
| `IceCreamDataNew.csv` | Extension dataset concatenated in assignment 5 |
| `CustomerData.csv` | Customer demographic data merged by ID |
| `Fish1-2.csv` / `Fish2-2.csv` | Fish population datasets used in earlier exercises |

---

## Tools

`Python 3` · `Pandas` · `Jupyter Notebook` · `os` · `CSV`

---

*University of Denver · Daniels College of Business · INFO 3100*
