# 🤖 Machine Learning Projects

A collection of hands-on projects focused on building, training, evaluating, interpreting, and improving Machine Learning models using Python.

This folder documents my journey from foundational ML algorithms to practical predictive systems, reproducible model pipelines, and end-to-end Machine Learning applications.

> **Current status:** Project ideas and learning roadmap. Each project will be marked as completed as it is implemented, evaluated, and documented.

---

## 🎯 Objectives

- Understand supervised and unsupervised learning.
- Learn how to prepare datasets for Machine Learning.
- Build regression and classification models.
- Explore clustering and dimensionality reduction.
- Perform feature engineering and feature selection.
- Understand training, validation, and test datasets.
- Evaluate models using appropriate metrics.
- Detect overfitting and underfitting.
- Apply cross-validation and hyperparameter tuning.
- Interpret model predictions and limitations.
- Build reproducible Machine Learning pipelines.
- Develop foundations for Deep Learning, Generative AI, and MLOps.

---

## 🧰 Technologies

- **Language:** Python
- **Data processing:** NumPy, Pandas
- **Machine Learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Statistical analysis:** SciPy, Statsmodels
- **Experiment tracking:** MLflow (later projects)
- **Model persistence:** Joblib
- **Development tools:** Jupyter Notebook, VS Code
- **Testing:** pytest
- **Version control:** Git and GitHub

> Start with NumPy, Pandas, basic statistics, and Scikit-learn. Advanced frameworks and experiment-tracking tools can be introduced as projects become more complex.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | Student Marks Prediction | Simple Linear Regression | Planned |
| 02 | House Price Prediction | Multiple Linear Regression | Planned |
| 03 | Iris Flower Classification | Classification fundamentals | Planned |
| 04 | Titanic Survival Prediction | Binary classification, preprocessing | Planned |
| 05 | Diabetes Risk Prediction | Classification metrics and limitations | Planned |
| 06 | Used Car Price Prediction | Regression and feature engineering | Planned |
| 07 | Customer Purchase Prediction | Logistic Regression | Planned |
| 08 | Exam Score Prediction | Regression evaluation | Planned |

### 🟡 Intermediate Projects

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 09 | Customer Churn Prediction | Classification, recall, precision | Planned |
| 10 | Credit Risk Classification | Class imbalance, decision thresholds | Planned |
| 11 | Employee Attrition Prediction | Feature engineering, classification | Planned |
| 12 | Customer Segmentation | K-Means clustering | Planned |
| 13 | Mall Customer Segmentation | Clustering and visualization | Planned |
| 14 | Product Recommendation Baseline | Similarity and recommendation fundamentals | Planned |
| 15 | Spam Message Classification | Text preprocessing, TF-IDF, classification | Planned |
| 16 | Wine Quality Prediction | Regression and classification comparison | Planned |
| 17 | Loan Approval Prediction | Categorical encoding, model comparison | Planned |
| 18 | Feature Selection Benchmark | Feature importance, dimensionality reduction | Planned |

### 🔴 Advanced Projects

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 19 | End-to-End ML Pipeline | Preprocessing, training, evaluation, persistence | Planned |
| 20 | Hyperparameter Optimization Study | Cross-validation, Grid Search, Randomized Search | Planned |
| 21 | Imbalanced Classification Benchmark | Resampling, thresholds, PR-AUC | Planned |
| 22 | Time-Series Forecasting Baseline | Temporal features, chronological validation | Planned |
| 23 | Model Explainability Explorer | Permutation importance, SHAP exploration | Planned |
| 24 | Anomaly Detection Toolkit | Isolation Forest, anomaly evaluation | Planned |
| 25 | Ensemble Model Comparison | Random Forest, Gradient Boosting | Planned |
| 26 | Model Drift Monitoring Prototype | Data drift, prediction monitoring | Planned |
| 27 | Reproducible ML Experiment Tracker | Experiment logging, model comparisons | Planned |
| 28 | ML Model Deployment API | Model serialization, FastAPI integration | Planned |

---

## 📚 Concepts Covered

### 1. Machine Learning Fundamentals
- What Machine Learning is and when to use it
- Supervised versus unsupervised learning
- Features and target variables
- Training, validation, and test datasets
- Generalization
- Overfitting and underfitting
- Bias-variance trade-off

### 2. Data Preparation
- Missing-value handling
- Duplicate and invalid record detection
- Numerical feature scaling
- Categorical feature encoding
- Train-test splitting
- Feature engineering
- Feature selection
- Data leakage prevention

### 3. Regression
- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting
- Regression evaluation metrics

**Metrics to understand:**
- MAE — Mean Absolute Error
- MSE — Mean Squared Error
- RMSE — Root Mean Squared Error
- \(R^2\) score

### 4. Classification
- Logistic Regression
- K-Nearest Neighbors
- Decision Trees
- Random Forest
- Support Vector Machines
- Naive Bayes
- Gradient Boosting classifiers

**Metrics to understand:**
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- ROC-AUC
- Precision-recall curves

### 5. Unsupervised Learning
- K-Means clustering
- Hierarchical clustering
- DBSCAN
- Principal Component Analysis (PCA)
- Cluster evaluation
- Dimensionality reduction
- Interpreting discovered groups

### 6. Model Evaluation and Improvement
- Baseline models
- Cross-validation
- Hyperparameter tuning
- Grid Search and Randomized Search
- Class imbalance
- Decision-threshold selection
- Error analysis
- Model comparison

### 7. Feature Engineering and Pipelines
- Numerical and categorical transformations
- Scikit-learn `Pipeline`
- `ColumnTransformer`
- Reusable preprocessing workflows
- Consistent training and inference transformations
- Reproducible experiments

### 8. Model Interpretation and Reliability
- Feature importance
- Permutation importance
- Partial dependence
- SHAP fundamentals
- Data leakage
- Model limitations and uncertainty
- Fairness considerations
- Monitoring data and prediction drift

### 9. Model Persistence and Deployment Foundations
- Saving and loading trained models
- Joblib
- Reproducible inference
- Input validation
- Prediction APIs
- Model versioning
- Basic monitoring

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
09_Machine_Learning_Projects/
│
├── README.md
│
├── 01_student_marks_prediction/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   │   ├── data_preprocessing.py
│   │   ├── train.py
│   │   └── evaluate.py
│   ├── models/
│   ├── tests/
│   ├── outputs/
│   └── requirements.txt
│
├── 02_house_price_prediction/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   ├── tests/
│   └── outputs/
│
└── ...
```

**Folder guidelines:**

- `data/` — small sample datasets or instructions for obtaining data.
- `notebooks/` — experiments and exploratory analysis.
- `src/` — reusable preprocessing, training, and evaluation code.
- `models/` — saved model artifacts when appropriate; avoid committing large files.
- `tests/` — tests for preprocessing, predictions, and important functions.
- `outputs/` — evaluation reports and visualizations.
- `README.md` — objective, dataset, methodology, metrics, results, and limitations.
- `requirements.txt` — project-specific dependencies.

For small beginner projects, a notebook and README are enough. Introduce separate modules and tests as the project grows.

---

## ✅ Project Completion Checklist

- [ ] Define the prediction or analysis problem.
- [ ] Identify the dataset and document its source.
- [ ] Perform exploratory data analysis.
- [ ] Clean and validate the data.
- [ ] Define features and target variables.
- [ ] Split data appropriately before fitting preprocessing steps.
- [ ] Establish a simple baseline model.
- [ ] Train at least one suitable model.
- [ ] Select metrics appropriate to the problem.
- [ ] Evaluate on data not used for model fitting or tuning.
- [ ] Check for overfitting, leakage, and major failure cases.
- [ ] Compare models when useful.
- [ ] Explain the results and limitations.
- [ ] Save the model and preprocessing pipeline if needed.
- [ ] Add tests and reproducible setup instructions.
- [ ] Document findings and commit the project to GitHub.

---

## 🗺️ Recommended Learning Order

1. **Student Marks Prediction** — understand features, targets, and regression.
2. **House Price Prediction** — learn multiple features and regression metrics.
3. **Iris Flower Classification** — practise classification and evaluation.
4. **Titanic Survival Prediction** — learn preprocessing and categorical encoding.
5. **Customer Churn Prediction** — understand precision, recall, and F1-score.
6. **Customer Segmentation** — explore unsupervised learning.
7. **Spam Message Classification** — apply basic text preprocessing and TF-IDF.
8. **End-to-End ML Pipeline** — combine preprocessing, training, and evaluation.
9. **Hyperparameter Optimization Study** — improve model selection.
10. **ML Model Deployment API** — prepare a trained model for use by an application.

**Recommendation:** Start with Scikit-learn before moving to Deep Learning frameworks. Understand why a model works, how it is evaluated, and where it fails—not just how to call `fit()` and `predict()`.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 28 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with documented evaluation | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [SQL Projects](../05_SQL_Projects/README.md)
- [Statistics Projects](../06_Statistics_Projects/README.md)
- [EDA and Visualization Projects](../07_EDA_Visualization_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [Deployment, Cloud, and MLOps](../15_Deployment_Cloud_MLOps/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Understand the problem → Prepare the data → Establish a baseline → Train the model → Evaluate honestly → Investigate errors → Improve carefully.**

The goal is not simply to achieve a high score. It is to build Machine Learning systems that generalize to unseen data, produce meaningful results, and have clearly documented limitations.
