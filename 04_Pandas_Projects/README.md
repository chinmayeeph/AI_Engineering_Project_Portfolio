# 🐼 Pandas Projects

A collection of hands-on projects built with **Python and Pandas** to develop practical data manipulation, cleaning, transformation, and analysis skills for Data Analytics, Data Science, and AI/ML Engineering.

This folder documents my journey from learning Pandas fundamentals to building reusable data-processing workflows and portfolio-ready projects.

> **Current status:** Project ideas and learning roadmap. Each project will be marked as completed as it is implemented, tested, and documented.

---

## 🎯 Objectives

- Learn to load and inspect real-world datasets.
- Clean missing, duplicate, inconsistent, and incorrectly formatted data.
- Filter, sort, group, aggregate, and transform datasets.
- Combine multiple datasets using merges, joins, and concatenation.
- Work with dates, strings, categorical data, and numerical columns.
- Perform exploratory data analysis (EDA) using Pandas.
- Export clean datasets and analysis results.
- Build a strong foundation for SQL, visualization, Machine Learning, and AI pipelines.

---

## 🧰 Technologies

- **Language:** Python
- **Primary library:** Pandas
- **Supporting libraries:** NumPy, Matplotlib, Seaborn
- **Data formats:** CSV, Excel, JSON
- **Development tools:** VS Code, Jupyter Notebook, Git, GitHub
- **Testing:** pytest

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced so that each project builds on previously learned concepts.

### 🟢 Beginner Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 01 | Student Marks Analyzer | DataFrames, filtering, sorting, aggregation | Planned |
| 02 | CSV Data Inspector | `read_csv()`, `head()`, `info()`, `describe()` | Planned |
| 03 | Data Cleaning Toolkit | Missing values, duplicates, data types | Planned |
| 04 | Personal Expense Analyzer | Grouping, aggregation, dates, categories | Planned |
| 05 | Sales Summary Analyzer | GroupBy, sorting, summary statistics | Planned |
| 06 | Employee Data Analyzer | Filtering, conditional selection, sorting | Planned |
| 07 | Movie Ratings Analyzer | GroupBy, rankings, averages | Planned |
| 08 | Weather Data Analyzer | Date handling, filtering, time-based summaries | Planned |

### 🟡 Intermediate Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 09 | E-Commerce Orders Analysis | Merging customers, orders, and products | Planned |
| 10 | Customer Segmentation Explorer | Aggregations, feature creation, customer summaries | Planned |
| 11 | Retail Inventory Analyzer | Stock calculations, joins, conditional logic | Planned |
| 12 | Job Market Data Analyzer | String cleaning, missing values, grouping | Planned |
| 13 | COVID-19 Trends Analyzer | Time series, resampling, rolling calculations | Planned |
| 14 | Bank Transactions Analyzer | Dates, categories, reconciliation | Planned |
| 15 | Multi-File Data Consolidator | Concatenation, file processing, validation | Planned |
| 16 | Data Quality Report Generator | Validation rules, duplicates, missing-value reports | Planned |

### 🔴 Advanced Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 17 | End-to-End Data Cleaning Pipeline | Reusable transformations, validation, logging | Planned |
| 18 | Automated Business KPI Report | Multi-table analysis, reusable summaries, exports | Planned |
| 19 | Time-Series Sales Forecasting Preparation | Dates, resampling, lag and rolling features | Planned |
| 20 | ML Dataset Preparation Pipeline | Feature engineering, encoding, missing-value handling | Planned |
| 21 | Large CSV Processing Benchmark | Memory usage, data types, performance | Planned |
| 22 | Reusable Pandas Data Quality Package | Functions, modular code, tests | Planned |

---

## 📚 Pandas Concepts Covered

### 1. DataFrame and Series Fundamentals
- Creating Series and DataFrames
- Reading CSV, Excel, and JSON files
- Inspecting datasets with `head()`, `tail()`, `info()`, and `describe()`
- Selecting columns and rows
- Using `.loc` and `.iloc`

### 2. Data Cleaning
- Identifying and handling missing values
- Removing duplicate records
- Renaming columns
- Converting data types
- Cleaning inconsistent text and category values
- Detecting invalid and out-of-range values

### 3. Data Selection and Transformation
- Boolean filtering
- Sorting rows and columns
- Creating and modifying columns
- Applying conditional logic
- Using `map()`, `apply()`, and vectorized operations appropriately

### 4. Grouping and Aggregation
- `groupby()`
- `agg()`
- `value_counts()`
- `pivot_table()`
- `crosstab()`
- Calculating totals, averages, counts, minimums, and maximums

### 5. Combining Datasets
- `merge()`
- `join()`
- `concat()`
- Understanding join types
- Handling unmatched keys and duplicate join keys

### 6. Dates and Text Processing
- Converting strings into datetime values
- Extracting year, month, and day
- Filtering by date ranges
- Resampling time-series data
- Cleaning text with the `.str` accessor

### 7. Data Analysis and Export
- Calculating business metrics
- Identifying trends and outliers
- Preparing data for visualization
- Exporting CSV and Excel reports
- Creating reproducible data-processing workflows

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
04_Pandas_Projects/
│
├── README.md
│
├── 01_student_marks_analyzer/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   ├── tests/
│   ├── outputs/
│   └── requirements.txt
│
├── 02_csv_data_inspector/
│   ├── README.md
│   ├── data/
│   ├── src/
│   └── tests/
│
├── 03_data_cleaning_toolkit/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   └── tests/
│
└── ...
```

**Folder guidelines:**
- `data/` — sample datasets; avoid committing private or sensitive data.
- `notebooks/` — exploratory work and learning experiments.
- `src/` — reusable Python code.
- `tests/` — automated tests.
- `outputs/` — generated reports and processed results.
- `README.md` — project objective, setup instructions, methodology, and findings.
- `requirements.txt` — project-specific dependencies when needed.

For small beginner exercises, a single Python file and README are sufficient. Add more folders as the project grows.

---

## ✅ Project Completion Checklist

Use this checklist for each project:

- [ ] Define the problem and expected output.
- [ ] Find or create a suitable dataset.
- [ ] Inspect the dataset before modifying it.
- [ ] Identify data-quality issues.
- [ ] Clean and transform the data.
- [ ] Perform the required analysis.
- [ ] Validate the results.
- [ ] Write reusable functions where appropriate.
- [ ] Add tests for important calculations and edge cases.
- [ ] Document the workflow and key findings.
- [ ] Add visualizations when they improve understanding.
- [ ] Upload the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

1. **Student Marks Analyzer** — learn DataFrames, filtering, sorting, and aggregation.
2. **CSV Data Inspector** — practice reading and inspecting datasets.
3. **Data Cleaning Toolkit** — handle missing values, duplicates, and data types.
4. **Personal Expense Analyzer** — analyze categories and monthly totals.
5. **Sales Summary Analyzer** — practice grouping and business metrics.
6. **E-Commerce Orders Analysis** — learn merges and joins.
7. **Data Quality Report Generator** — build validation and reporting logic.
8. **ML Dataset Preparation Pipeline** — prepare data for Machine Learning.

**Recommendation:** Start with small CSV datasets before attempting large or complex datasets. Focus on understanding each operation rather than memorizing every Pandas method.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 22 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with automated tests | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [SQL Projects](../05_SQL_Projects/README.md)
- [EDA and Visualization Projects](../07_EDA_Visualization_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Understand the data → Inspect the quality → Clean the data → Analyze the results → Validate the output → Document the findings.**

The goal is not simply to learn Pandas syntax. It is to develop the practical skills needed to turn raw data into reliable, useful information.
