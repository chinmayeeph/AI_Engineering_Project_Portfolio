# 📊 Exploratory Data Analysis (EDA) & Visualization Projects

A collection of hands-on projects focused on exploring datasets, identifying data-quality issues, discovering patterns, investigating relationships, and communicating findings through meaningful visualizations.

This folder documents my journey from basic exploratory analysis to end-to-end analytical investigations using Python, Pandas, NumPy, Matplotlib, and Seaborn.

> **Current status:** Project ideas and learning roadmap. Each project will be marked as completed as it is implemented, validated, and documented.

---

## 🎯 Objectives

- Understand unfamiliar datasets systematically.
- Identify missing values, duplicates, outliers, and inconsistent data.
- Summarize numerical and categorical variables.
- Discover trends, distributions, relationships, and anomalies.
- Select appropriate visualizations for different analytical questions.
- Perform univariate, bivariate, and multivariate analysis.
- Investigate correlations without confusing them with causation.
- Develop business insights supported by data.
- Communicate findings through charts, reports, and dashboards.
- Prepare high-quality datasets for statistical analysis and Machine Learning.

---

## 🧰 Technologies

- **Language:** Python
- **Data manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Interactive notebooks:** Jupyter Notebook
- **Optional dashboard tools:** Power BI, Tableau, Streamlit
- **Development tools:** VS Code, Git, GitHub
- **Testing:** pytest

> Start with Matplotlib and Seaborn. Explore Plotly and dashboard tools after becoming comfortable with the fundamentals.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 01 | Student Performance EDA | Distributions, averages, categorical comparisons | Planned |
| 02 | Netflix Movies and TV Shows Analysis | Categories, release years, content trends | Planned |
| 03 | Sales Data Exploration | Revenue trends, product comparisons, rankings | Planned |
| 04 | Weather Data Visualization | Time trends, temperature distributions | Planned |
| 05 | Population and Demographics Analysis | Histograms, comparisons, percentages | Planned |
| 06 | Personal Expense Visualization | Spending categories, monthly patterns | Planned |
| 07 | Sports Performance EDA | Rankings, distributions, player comparisons | Planned |
| 08 | Data Quality Visualization Report | Missing values, duplicates, outlier inspection | Planned |

### 🟡 Intermediate Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 09 | E-Commerce Customer Behavior Analysis | Customer activity, purchasing patterns | Planned |
| 10 | Airbnb Listings EDA | Price distributions, location, availability | Planned |
| 11 | Customer Churn Exploration | Churn patterns, group comparisons, associations | Planned |
| 12 | Employee Attrition Analysis | Workforce trends, categorical relationships | Planned |
| 13 | Food Delivery Performance Analysis | Delivery times, delays, cancellations | Planned |
| 14 | Housing Price EDA | Price distributions, feature relationships | Planned |
| 15 | Job Market and Salary Analysis | Salary ranges, job categories, skill demand | Planned |
| 16 | Marketing Campaign EDA | Engagement, conversions, campaign comparisons | Planned |

### 🔴 Advanced Projects

| No. | Project | Key Concepts | Status |
|---|---|---|---|
| 17 | End-to-End Retail Business Analysis | Multiple datasets, business KPIs, recommendations | Planned |
| 18 | Customer Cohort and Retention Visualization | Cohort tables, heatmaps, retention trends | Planned |
| 19 | Multivariate Feature Exploration | Pair plots, correlation, feature relationships | Planned |
| 20 | Time-Series Exploratory Analysis | Trend, seasonality, rolling statistics | Planned |
| 21 | Anomaly and Outlier Investigation | Robust statistics, anomaly visualization | Planned |
| 22 | Interactive EDA Dashboard | Interactive filters, Plotly, Streamlit | Planned |
| 23 | Automated EDA Report Generator | Reusable analysis, generated charts, HTML reports | Planned |
| 24 | ML Dataset Exploratory Analysis | Target analysis, leakage checks, feature distributions | Planned |

---

## 📚 Concepts Covered

### 1. Understanding a Dataset
- Dataset dimensions and structure
- Column names and data types
- Numerical versus categorical variables
- Descriptive statistics
- Unique values and category frequencies
- Initial data-quality checks

### 2. Data Cleaning and Quality
- Missing-value analysis
- Duplicate detection
- Incorrect data types
- Inconsistent categories and text
- Invalid values and impossible ranges
- Outlier investigation
- Data-quality summary reports

### 3. Univariate Analysis
Studying one variable at a time.

- Histograms
- Box plots
- Bar charts and count plots
- Density plots
- Frequency distributions
- Percentiles, skewness, and spread

### 4. Bivariate Analysis
Studying relationships between two variables.

- Scatter plots
- Grouped bar charts
- Box plots by category
- Line charts
- Correlation analysis
- Cross-tabulations

### 5. Multivariate Analysis
Studying several variables together.

- Correlation heatmaps
- Pair plots
- Grouped comparisons
- Faceted visualizations
- Numerical and categorical feature relationships
- Confounding factors and limitations

### 6. Time-Series Exploration
- Trends over time
- Daily, monthly, and yearly aggregation
- Rolling averages
- Seasonality
- Time-based comparisons
- Missing dates and irregular observations

### 7. Visualization Design
- Choosing a suitable chart type
- Clear titles and axis labels
- Appropriate scales and units
- Legends and annotations
- Color accessibility
- Avoiding misleading visualizations
- Highlighting the main analytical finding

### 8. Communicating Insights
- Converting observations into findings
- Distinguishing facts from assumptions
- Supporting conclusions with evidence
- Explaining limitations
- Writing concise executive summaries
- Providing practical recommendations

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
07_EDA_Visualization_Projects/
│
├── README.md
│
├── 01_student_performance_eda/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   │   └── exploratory_analysis.ipynb
│   ├── src/
│   ├── outputs/
│   │   └── figures/
│   └── requirements.txt
│
├── 02_sales_data_exploration/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── outputs/
│   │   └── figures/
│   └── src/
│
├── 03_data_quality_visualization/
│   ├── README.md
│   ├── notebooks/
│   ├── src/
│   ├── tests/
│   └── outputs/
│
└── ...
```

**Folder guidelines:**

- `data/` — datasets or instructions for obtaining them.
- `notebooks/` — step-by-step exploratory analysis.
- `src/` — reusable cleaning, analysis, and visualization functions.
- `outputs/figures/` — exported charts.
- `tests/` — tests for reusable calculations and transformations.
- `README.md` — objective, dataset source, analysis, findings, and limitations.
- `requirements.txt` — project-specific dependencies when needed.

For beginner projects, a single notebook, a dataset, and a README are enough. Add more structure when the project grows.

---

## ✅ Project Completion Checklist

- [ ] Define the analytical questions before creating charts.
- [ ] Identify and document the dataset source.
- [ ] Inspect the shape, columns, and data types.
- [ ] Assess missing values and duplicates.
- [ ] Investigate unusual values and outliers.
- [ ] Clean the data where necessary and document changes.
- [ ] Calculate relevant summary statistics.
- [ ] Perform univariate analysis.
- [ ] Explore important relationships between variables.
- [ ] Create clearly labelled, appropriate visualizations.
- [ ] Document at least three meaningful findings.
- [ ] Explain limitations and avoid unsupported causal claims.
- [ ] Add a concise conclusion or recommendations.
- [ ] Save important charts and document how to reproduce the analysis.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

1. **Student Performance EDA** — learn the complete exploratory workflow.
2. **Sales Data Exploration** — analyse categories, revenue, and trends.
3. **Data Quality Visualization Report** — inspect missing values and outliers.
4. **Netflix Movies and TV Shows Analysis** — practise categorical and time-based analysis.
5. **Housing Price EDA** — investigate relationships between numerical features.
6. **Customer Churn Exploration** — compare groups and investigate associations.
7. **Customer Cohort and Retention Visualization** — explore retention patterns.
8. **Interactive EDA Dashboard** — present findings through interactive charts.
9. **Automated EDA Report Generator** — convert repeated analysis steps into a reusable workflow.

**Recommendation:** Complete one project thoroughly before starting the next. A small project with clean code, appropriate charts, and clear findings is more valuable than many unfinished notebooks.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 24 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with documented findings | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [SQL Projects](../05_SQL_Projects/README.md)
- [Statistics Projects](../06_Statistics_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Ask a question → Inspect the data → Clean and validate → Explore patterns → Visualize findings → Communicate insights.**

The goal is not to create charts simply for appearance. It is to use visualizations to understand data, investigate meaningful questions, and communicate reliable conclusions.
