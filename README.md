# Python Data Analysis

**Finley Hardie** · University of Denver, Daniels College of Business
Portfolio site: **[finleyhardie-bit.github.io](https://finleyhardie-bit.github.io)**

Python and pandas work from INFO 3100 (Automating Business Processes with Python, Winter 2026).

| Folder | What's inside |
|---|---|
| [`nba-player-performance/`](nba-player-performance) | Main course project: what drives NBA scoring? |
| [`ice-cream-sales-wrangling/`](ice-cream-sales-wrangling) | Combining and summarizing retail sales from three stores |
| [`python-fundamentals/`](python-fundamentals) | Shorter exercises that built up to the project |

---

## NBA player performance analysis

**Notebook:** [`nba-player-performance-analysis.ipynb`](nba-player-performance/nba-player-performance-analysis.ipynb) · **Data:** `players.csv`, `stats.csv`

Using 50 players from the 2023–24 season, I asked three questions:

1. Do positions (PG, SG, SF, PF, C) differ in average points per game?
2. Do players who play more minutes score more?
3. Do Eastern and Western Conference players differ in assists?

**Findings**
- Point guards scored the most on average (18.77 points per game).
- Minutes and points are strongly related (r = 0.64).
- Conference made essentially no difference to assists (East 4.29, West 4.28).

**Techniques:** merging tables, descriptive statistics, `groupby`, crosstabs, Pearson correlation.

> Not to be confused with my INFO 3300 data warehousing project (NBA jersey *sales*), which will live in [data-warehousing-bi](https://github.com/finleyhardie-bit/data-warehousing-bi).

## Ice cream sales data wrangling

**Notebook:** [`ice-cream-sales-data-wrangling.ipynb`](ice-cream-sales-wrangling/ice-cream-sales-data-wrangling.ipynb) · **Data:** `IceCreamData.csv`, `IceCreamDataNew.csv`, `CustomerData.csv`

Retail sales from three Colorado stores (Denver, Greeley, Parker).
- Combined two sales files and merged in customer data by ID.
- Summarized sales by flavor, store and customer type.
- Wrote a reusable `column_summaries()` function that returns numeric or categorical summaries for any DataFrame.
- Built pivot tables of transactions by store and customer segment.

## Python fundamentals

| Notebook | Focus |
|---|---|
| [`data-frame-basics-project.ipynb`](python-fundamentals/data-frame-basics-project.ipynb) | Input, variables and building DataFrames |
| [`loop-and-conditions.ipynb`](python-fundamentals/loop-and-conditions.ipynb) | Loops, conditionals and list comprehensions |
| [`data-functions-project.ipynb`](python-fundamentals/data-functions-project.ipynb) | Writing functions to process data |

**Tools:** Python 3, pandas, Jupyter Notebook
