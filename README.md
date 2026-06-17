# Demographic Data Analyzer

This project was built as part of freeCodeCamp's **Data Analysis with Python** certification.

It uses **Pandas** to analyze demographic data extracted from the 1994 Census database.

## What it does

The `calculate_demographic_data()` function in `demographic_data_analyzer.py` reads `adult.data.csv` and answers the following questions:

- How many people of each race are represented in the dataset?
- What is the average age of men?
- What is the percentage of people who have a Bachelor's degree?
- What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
- What percentage of people without advanced education make more than 50K?
- What is the minimum number of hours a person works per week?
- What percentage of people who work the minimum number of hours per week have a salary of more than 50K?
- What country has the highest percentage of people that earn >50K, and what is that percentage?
- What is the most popular occupation for those who earn >50K in India?

## Files

- `demographic_data_analyzer.py` — main solution
- `adult.data.csv` — dataset
- `main.py` — runs the function and the unit tests
- `test_module.py` — unit tests for the project

## How to run

```bash
python main.py
```

## Dataset Source

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.
