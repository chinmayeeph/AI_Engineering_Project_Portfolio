# 🔢 NumPy Projects

Welcome to the NumPy Projects section of my AI Engineering portfolio!

This folder contains practical projects and experiments using NumPy, Python's fundamental library for numerical computing. The projects focus on efficient array operations, mathematical computation, data manipulation, and numerical problem-solving.

My goal is to develop a strong understanding of NumPy as a foundation for data analysis, scientific computing, Machine Learning, and AI Engineering.

## 🎯 Objectives

- Understand NumPy arrays and their differences from Python lists.
- Create and manipulate one-dimensional and multidimensional arrays.
- Apply indexing, slicing, reshaping, and broadcasting.
- Perform vectorized operations without unnecessary Python loops.
- Use statistical and mathematical functions on numerical data.
- Understand array dimensions, axes, shapes, and data types.
- Apply linear algebra operations to practical problems.
- Compare vectorized NumPy operations with equivalent Python implementations.
- Write readable, testable, and reproducible numerical code.

## 📂 Projects and Experiments

Projects will be added as they are implemented, tested, and documented.

| # | Project | Description | Key Concepts | Status |
|---|---|---|---|---|
| 01 | Student Marks Analyzer | Calculate subject-wise and student-wise performance statistics. | Arrays, indexing, aggregation | Planned |
| 02 | Array Operations Toolkit | Demonstrate common array creation, manipulation, and transformation operations. | Array creation, shape, reshape | Planned |
| 03 | Statistical Summary Calculator | Calculate mean, median, variance, standard deviation, and percentiles. | Statistics, aggregation | Planned |
| 04 | NumPy Performance Benchmark | Compare Python loops, list operations, and NumPy vectorization. | Vectorization, timing | Planned |
| 05 | Sales Data Analyzer | Analyze sales figures using multidimensional arrays. | Slicing, axes, aggregation | Planned |
| 06 | Image Array Processor | Perform basic numerical transformations on image arrays. | Array dimensions, data types, clipping | Planned |
| 07 | Matrix Operations Toolkit | Implement matrix multiplication and other matrix computations. | Matrix operations, linear algebra | Planned |
| 08 | Random Data Simulator | Generate reproducible random data for experiments. | Random sampling, seeds, distributions | Planned |
| 09 | Missing Value Analyzer | Identify and handle missing or invalid numerical values. | Boolean masks, NaN handling | Planned |
| 10 | Normalization and Scaling Toolkit | Apply common numerical scaling methods. | Min-max scaling, standardization | Planned |
| 11 | Monte Carlo Simulation | Estimate numerical quantities using repeated random sampling. | Probability, random arrays, simulation | Planned |
| 12 | Linear Algebra Explorer | Explore determinants, matrix rank, eigenvalues, and solving linear systems. | `numpy.linalg` | Planned |
| 13 | Correlation Analyzer | Calculate correlations between numerical variables. | Covariance, correlation matrices | Planned |
| 14 | Distance Calculator | Calculate Euclidean and other vector distances. | Vector operations, norms | Planned |
| 15 | Synthetic Dataset Generator | Generate reproducible numerical datasets for ML experiments. | Random generation, shapes, distributions | Planned |

> **Status note:** These are planned project ideas, not completed projects. Update each status as you build, test, and document the implementation.

## 🧠 NumPy Topics Covered

### 1. Array Fundamentals
- Creating arrays with `np.array()`
- Array attributes: `ndim`, `shape`, `size`, and `dtype`
- Data types and type conversion
- Zeros, ones, full arrays, and identity matrices
- `arange()` and `linspace()`

### 2. Indexing and Manipulation
- Indexing and slicing
- Boolean indexing and filtering
- Fancy indexing
- Reshaping and flattening
- Transposing arrays
- Joining and splitting arrays
- Sorting and searching

### 3. Vectorized Computation
- Arithmetic operations
- Universal functions (ufuncs)
- Broadcasting rules
- Aggregation along axes
- Conditional operations with `np.where()`
- Avoiding unnecessary Python loops

### 4. Statistics and Numerical Analysis
- Mean, median, and percentiles
- Variance and standard deviation
- Minimum, maximum, and sums
- Cumulative sums and products
- Correlation and covariance
- Missing and non-finite values

### 5. Linear Algebra
- Vector and matrix operations
- Dot products and matrix multiplication
- Matrix transposition
- Determinants and matrix rank
- Solving linear systems
- Eigenvalues and eigenvectors
- Vector norms

### 6. Random Number Generation
- Random integers and floating-point values
- Random sampling
- Reproducible experiments with random seeds
- Common probability distributions
- Simulation and Monte Carlo methods

### 7. Numerical Efficiency
- Vectorization versus Python loops
- Memory usage and array data types
- Performance benchmarking
- Numerical precision and floating-point behavior

## 🛠️ Tools and Technologies

- **Language:** Python
- **Numerical computing:** NumPy
- **Editor:** Visual Studio Code
- **Interactive experimentation:** Jupyter Notebook
- **Testing:** pytest
- **Version control:** Git and GitHub
- **Visualization:** Matplotlib, when useful

## 📁 Suggested Project Structure

```text
03_NumPy_Projects/
├── README.md
├── Student_Marks_Analyzer/
│   ├── README.md
│   ├── src/
│   │   └── student_marks.py
│   ├── tests/
│   │   └── test_student_marks.py
│   └── notebooks/
│       └── exploration.ipynb
├── NumPy_Performance_Benchmark/
│   ├── README.md
│   ├── src/
│   │   └── benchmark.py
│   └── results/
│       └── README.md
├── Matrix_Operations_Toolkit/
│   ├── README.md
│   ├── src/
│   └── tests/
├── Statistical_Summary_Calculator/
│   ├── README.md
│   ├── src/
│   └── tests/
└── ...
```

This is a suggested structure. Create each project folder when you start implementing it. Notebooks and result files are optional and should be included when they add value.

## 📊 Project Documentation Standard

For each project, document:

1. **Problem statement:** What numerical problem are you solving?
2. **Dataset or inputs:** What data does the project use?
3. **Approach:** Explain the steps and relevant NumPy concepts.
4. **Implementation:** Provide readable Python code.
5. **Example output:** Show representative results.
6. **Testing:** Validate calculations and edge cases.
7. **Performance:** Benchmark the code when relevant.
8. **Limitations:** Explain assumptions, numerical precision, and constraints where appropriate.

## ✅ Project Completion Checklist

- [ ] Understand the NumPy concepts used.
- [ ] Implement the solution and verify the results.
- [ ] Test empty arrays and unexpected dimensions where relevant.
- [ ] Check array shapes and data types.
- [ ] Validate numerical results against known examples.
- [ ] Handle NaN and infinity values where appropriate.
- [ ] Document the approach and example output.
- [ ] Include tests and benchmarks where useful.
- [ ] Avoid committing private datasets or unnecessary large files.

## 🚀 Learning Roadmap

1. Learn array creation, dimensions, shapes, and data types.
2. Practice indexing, slicing, reshaping, and Boolean filtering.
3. Master broadcasting, vectorization, and axis-based operations.
4. Apply statistical and mathematical functions.
5. Learn matrix operations and linear algebra fundamentals.
6. Explore random number generation and simulation.
7. Build small analytical projects and benchmark selected operations.
8. Apply NumPy to Pandas, scientific computing, and Machine Learning.

## 🔗 Related Repository

Daily lessons, exercises, and learning progress are documented in the [180 Days AI Engineer Journey](https://github.com/chinmayeeph/180_Days_AI_Engineer_Journey).

This portfolio focuses on practical implementations and documented projects rather than duplicating every daily exercise.

## 📌 Note

Projects will be added incrementally as concepts are learned, implemented, and tested. The emphasis is on numerical correctness, efficient computation, reproducibility, and understanding why each operation works.