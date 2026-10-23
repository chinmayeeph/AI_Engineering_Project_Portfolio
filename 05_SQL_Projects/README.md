# 🗃️ SQL Projects

A collection of hands-on projects focused on querying, cleaning, transforming, and analyzing relational data using SQL.

This folder documents my journey from writing basic SQL queries to solving business problems, analyzing large datasets, designing reliable queries, and preparing data for Data Analytics, Data Science, and AI/ML Engineering workflows.

> **Current status:** Project ideas and learning roadmap. Each project will be marked as completed as it is implemented, tested, and documented.

---

## 🎯 Objectives

- Understand relational databases and database fundamentals.
- Retrieve data using `SELECT`, `WHERE`, `ORDER BY`, and `LIMIT`.
- Summarize data using aggregate functions and `GROUP BY`.
- Combine related tables using different types of joins.
- Write queries using subqueries and Common Table Expressions (CTEs).
- Analyze business metrics using SQL.
- Apply window functions to ranking, trends, and comparisons.
- Clean and validate data using SQL.
- Improve query readability, correctness, and performance.
- Prepare datasets for dashboards, statistical analysis, and Machine Learning.

---

## 🧰 Technologies

- **Query language:** SQL
- **Database systems:** PostgreSQL, SQLite, MySQL
- **Optional tools:** DBeaver, pgAdmin, SQLite Browser
- **Data visualization:** Power BI, Tableau, or Python
- **Version control:** Git and GitHub

> **Note:** SQL syntax varies slightly between database systems. Each project should identify the database used and document any database-specific features.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced, with an emphasis on practical business and analytical problems.

### 🟢 Beginner Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 01 | Student Database Analysis | `SELECT`, `WHERE`, `ORDER BY` | Planned |
| 02 | Employee Records Analysis | Filtering, sorting, aliases | Planned |
| 03 | Sales Summary Analysis | Aggregates, `GROUP BY`, `HAVING` | Planned |
| 04 | Library Management Database | Tables, primary keys, foreign keys | Planned |
| 05 | Personal Expense Analysis | Conditional aggregation, date filters | Planned |
| 06 | Movie Ratings Database | Joins, averages, rankings | Planned |
| 07 | Basic Customer Analysis | `DISTINCT`, filtering, aggregation | Planned |
| 08 | Product Inventory Analysis | Stock levels, conditional logic | Planned |

### 🟡 Intermediate Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 09 | E-Commerce Orders Analysis | Multi-table joins, revenue analysis | Planned |
| 10 | Customer Retention Analysis | Date calculations, cohorts, repeat purchases | Planned |
| 11 | Monthly Sales Trend Analysis | Date functions, CTEs, aggregation | Planned |
| 12 | HR Workforce Analytics | Grouping, subqueries, employee metrics | Planned |
| 13 | Marketing Campaign Analysis | Conversion rates, conditional aggregation | Planned |
| 14 | Banking Transactions Analysis | Transaction summaries, reconciliation | Planned |
| 15 | Food Delivery Performance Analysis | Delivery time, cancellations, service metrics | Planned |
| 16 | Product Performance Analysis | Ranking, category comparisons, profitability | Planned |

### 🔴 Advanced Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 17 | Customer Segmentation Using SQL | CTEs, aggregations, RFM metrics | Planned |
| 18 | Cohort Retention Analysis | Cohort grouping, retention rates | Planned |
| 19 | Advanced Sales Analytics | Window functions, running totals, moving averages | Planned |
| 20 | Funnel Conversion Analysis | Multi-step events, conversion rates | Planned |
| 21 | A/B Test Results Analysis | Group comparisons, statistical metric preparation | Planned |
| 22 | SQL Data Quality Audit | Null checks, duplicate checks, integrity validation | Planned |
| 23 | Query Optimization Lab | Indexes, query plans, performance comparisons | Planned |
| 24 | End-to-End Analytics Database | Schema design, SQL analysis, documented insights | Planned |

---

## 📚 SQL Concepts Covered

### 1. SQL Fundamentals
- `SELECT` and `DISTINCT`
- `WHERE`, `AND`, `OR`, and `NOT`
- `IN`, `BETWEEN`, and `LIKE`
- `ORDER BY` and `LIMIT`
- Column aliases
- `NULL` values and `IS NULL`

### 2. Aggregate Functions
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()` and `MAX()`
- `GROUP BY`
- `HAVING`
- Conditional aggregation using `CASE WHEN`

### 3. Joins and Relationships
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN` where supported
- `FULL OUTER JOIN` where supported
- Self joins
- Primary and foreign keys
- One-to-one, one-to-many, and many-to-many relationships
- Identifying unmatched records and duplicate join results

### 4. Subqueries and CTEs
- Scalar and correlated subqueries
- `EXISTS` and `NOT EXISTS`
- Common Table Expressions using `WITH`
- Breaking complex queries into readable steps
- Recursive CTEs where appropriate

### 5. Window Functions
- `ROW_NUMBER()`
- `RANK()` and `DENSE_RANK()`
- `LAG()` and `LEAD()`
- `SUM() OVER()`
- `AVG() OVER()`
- `PARTITION BY`
- Running totals and moving averages

### 6. Dates and Business Analytics
- Filtering date ranges
- Grouping by month, quarter, and year
- Month-over-month comparisons
- Year-over-year comparisons
- Revenue and order analysis
- Customer retention and repeat purchases
- Conversion and cancellation rates

### 7. Database Design and Data Quality
- `CREATE`, `ALTER`, and `DROP`
- `INSERT`, `UPDATE`, and `DELETE`
- Primary keys and foreign keys
- Constraints and normalization
- Duplicate and missing-value checks
- Transactions and safe data modifications

### 8. Query Performance
- Understanding indexes
- Reading query execution plans
- Avoiding unnecessary columns and joins
- Choosing appropriate filters
- Comparing alternative query approaches

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
05_SQL_Projects/
│
├── README.md
│
├── 01_student_database_analysis/
│   ├── README.md
│   ├── schema.sql
│   ├── data/
│   ├── queries/
│   │   ├── 01_basic_queries.sql
│   │   ├── 02_filtering_and_sorting.sql
│   │   └── 03_aggregations.sql
│   ├── results/
│   └── screenshots/
│
├── 02_employee_records_analysis/
│   ├── README.md
│   ├── schema.sql
│   ├── queries/
│   └── results/
│
├── 03_sales_summary_analysis/
│   ├── README.md
│   ├── schema.sql
│   ├── data/
│   ├── queries/
│   └── results/
│
└── ...
```

**Folder guidelines:**

- `schema.sql` — table definitions, relationships, and constraints.
- `data/` — small sample datasets or instructions for obtaining public datasets.
- `queries/` — organized SQL scripts.
- `results/` — query outputs, summaries, or generated reports.
- `screenshots/` — optional evidence of results or visualizations.
- `README.md` — business problem, database setup, approach, findings, and limitations.

For small beginner projects, one `.sql` file and a README are enough. Add extra files when they serve a clear purpose.

---

## ✅ Project Completion Checklist

- [ ] Define a real-world question or business problem.
- [ ] Identify the dataset and database system.
- [ ] Document the tables and relationships.
- [ ] Load or create the sample data.
- [ ] Write readable, consistently formatted SQL queries.
- [ ] Validate important results against expected values.
- [ ] Handle `NULL` values and possible duplicate records correctly.
- [ ] Include comments for complex queries.
- [ ] Explain the business meaning of the results.
- [ ] Include sample outputs or screenshots when useful.
- [ ] Document how to reproduce the analysis.
- [ ] Commit the finished project to GitHub.

---

## 🗺️ Recommended Learning Order

1. **Student Database Analysis** — practise basic queries and filtering.
2. **Employee Records Analysis** — improve sorting and conditional logic.
3. **Sales Summary Analysis** — learn grouping and aggregate functions.
4. **Movie Ratings Database** — understand joins and relationships.
5. **E-Commerce Orders Analysis** — solve multi-table business problems.
6. **Monthly Sales Trend Analysis** — practise date functions and CTEs.
7. **Advanced Sales Analytics** — learn window functions.
8. **Customer Segmentation Using SQL** — combine several concepts to generate business insights.
9. **Query Optimization Lab** — learn how to investigate slow queries.

**Recommendation:** Master filtering, aggregation, and joins before moving to CTEs and window functions. Practise writing queries yourself rather than simply copying solutions.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 24 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with documented results | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [Statistics Projects](../06_Statistics_Projects/README.md)
- [EDA and Visualization Projects](../07_EDA_Visualization_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Understand the question → Understand the data → Write the query → Validate the result → Explain the insight.**

The goal is not just to memorize SQL syntax. It is to learn how to retrieve trustworthy data and turn it into useful, evidence-based decisions.
