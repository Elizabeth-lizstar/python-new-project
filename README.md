# Gapminder Life Expectancy & GDP Analysis

A beginner data analysis project exploring global trends in life expectancy and GDP per capita using the classic Gapminder dataset, built with pandas.

## About the Project

This notebook walks through loading, inspecting, and analyzing the Gapminder dataset — a well-known collection of country-level statistics spanning multiple decades. The goal was to practice core pandas skills: reading tabular data, subsetting, grouping, and aggregating to answer basic exploratory questions about global development trends.

## Dataset

- **Source:** Gapminder (`gapminder.tsv`), a tab-separated file
- **Columns:** `country`, `continent`, `year`, `lifeExp` (life expectancy), `pop` (population), `gdpPercap` (GDP per capita)
- **Rows:** 3,312 country-year observations

> Note: If you're running this yourself, download `gapminder.tsv` and update the file path in the first cell to match your local setup.

## What the Analysis Covers

- Loading and inspecting the dataset (`head()`, `tail()`, `dtypes`)
- Selecting individual columns and subsets of columns
- Grouping by `year` to compute mean life expectancy over time
- Grouping by `year` and `continent` to compare life expectancy and GDP per capita across regions
- Counting unique countries per continent

## Key Takeaways

- Global average life expectancy shows a general upward trend across the observed years.
- Life expectancy and GDP per capita both vary significantly by continent, with Europe consistently among the highest and Africa generally lower, reflecting broader patterns of economic development.

## Tools Used

- Python
- pandas

## How to Run

1. Install the requirement:
   ```
   pip install pandas
   ```
2. Download `gapminder.tsv` and place it in your project folder (or update the file path in the notebook).
3. Open `new_project.ipynb` in Jupyter Notebook or JupyterLab and run all cells.

## Author

Elizabeth Akinleye
