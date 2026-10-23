# 🔬 Research and Experiments

A collection of hands-on experiments focused on machine learning research, algorithm comparisons, model evaluation, reproducibility, performance benchmarking, and evidence-based AI engineering.

This folder documents my journey from running small Python experiments to investigating machine learning methods, evaluating deep learning models, benchmarking LLM and RAG systems, and reproducing selected findings from published research.

> **Current status:** Research roadmap. Projects will be marked as completed after the experiment has been implemented, evaluated, and documented.

---

## 🎯 Objectives

- Develop a systematic approach to experimentation.
- Turn questions into testable hypotheses.
- Design controlled experiments with measurable outcomes.
- Establish baselines before introducing complexity.
- Compare algorithms using appropriate evaluation metrics.
- Understand random seeds, variability, and reproducibility.
- Investigate data preprocessing and feature engineering choices.
- Explore model architectures and hyperparameters.
- Benchmark runtime, memory use, inference latency, and cost.
- Read and reproduce selected findings from research papers.
- Evaluate LLM, RAG, and AI agent behavior systematically.
- Record failed experiments and unexpected results.
- Communicate conclusions with evidence, charts, and limitations.

---

## 🧰 Technologies and Tools

- **Programming:** Python
- **Numerical computing:** NumPy
- **Data analysis:** Pandas
- **Visualization:** Matplotlib, Seaborn
- **Machine learning:** Scikit-learn
- **Deep learning:** PyTorch
- **NLP and models:** Hugging Face Transformers
- **Experiment tracking:** MLflow or equivalent tools
- **Testing:** pytest
- **Benchmarking:** `timeit`, `time`, `cProfile`, `tracemalloc`
- **Version control:** Git and GitHub
- **Research sources:** arXiv, peer-reviewed publications, official documentation
- **LLM/RAG experiments:** Curated evaluation datasets and task-specific scripts

Start with Python, NumPy, Pandas, Matplotlib, and Scikit-learn. Introduce specialized tools only when an experiment benefits from them.

---

## 📂 Research and Experiment Roadmap

Projects are grouped by skill area and increasing complexity.

### 🟢 Beginner — Experimentation Fundamentals

| No. | Project | Research Question or Skill | Status |
|---|---|---|---|
| 01 | Python Loop vs Vectorization Benchmark | When does vectorization improve runtime? | Planned |
| 02 | List vs NumPy Array Experiment | How do operations and memory use differ? | Planned |
| 03 | Random Seed Reproducibility Lab | Which results vary between runs? | Planned |
| 04 | NumPy Data Type Precision Experiment | How do data types affect precision and memory? | Planned |
| 05 | Sorting Algorithm Benchmark | How does input size affect runtime? | Planned |
| 06 | Search Algorithm Comparison | When is each search method appropriate? | Planned |
| 07 | CSV Loading Performance Experiment | How do file size and parsing choices affect speed? | Planned |
| 08 | Missing Value Strategy Comparison | How do cleaning choices change results? | Planned |
| 09 | Outlier Handling Experiment | How sensitive are summaries to outliers? | Planned |
| 10 | Visualization Choice Experiment | Which chart best communicates a finding? | Planned |

### 🟡 Intermediate — Machine Learning Experiments

| No. | Project | Research Question or Skill | Status |
|---|---|---|---|
| 11 | Linear vs Logistic Regression | How do model assumptions and tasks differ? | Planned |
| 12 | Decision Tree Depth Experiment | How does model complexity affect generalization? | Planned |
| 13 | Random Forest vs Single Tree | Does ensembling improve test performance? | Planned |
| 14 | KNN Distance Metric Comparison | How does distance choice affect predictions? | Planned |
| 15 | Feature Scaling Experiment | Which models benefit from scaling? | Planned |
| 16 | Feature Selection Comparison | How does feature selection affect performance? | Planned |
| 17 | Missing Value Imputation Benchmark | How do imputation methods affect evaluation? | Planned |
| 18 | Class Imbalance Strategy Comparison | How do class weights and resampling affect results? | Planned |
| 19 | Cross-Validation Strategy Experiment | How stable are estimates across folds? | Planned |
| 20 | Hyperparameter Search Comparison | How do grid and randomized search compare? | Planned |
| 21 | Model Calibration Experiment | Do predicted probabilities match observed outcomes? | Planned |
| 22 | Threshold Optimization Experiment | How do thresholds affect precision and recall? | Planned |
| 23 | Learning Curve Analysis | Is the model data-limited or model-limited? | Planned |
| 24 | Error Analysis and Failure Categories | Which examples cause the most errors? | Planned |

### 🔵 Advanced — Deep Learning Experiments

| No. | Project | Research Question or Skill | Status |
|---|---|---|---|
| 25 | Activation Function Comparison | How do activation choices affect training? | Planned |
| 26 | Optimizer Comparison | How do optimizers affect convergence? | Planned |
| 27 | Learning Rate Experiment | How sensitive is training to learning rate? | Planned |
| 28 | Batch Size Experiment | How does batch size affect speed and generalization? | Planned |
| 29 | Weight Initialization Experiment | How does initialization affect optimization? | Planned |
| 30 | Regularization Comparison | How do dropout and weight decay affect overfitting? | Planned |
| 31 | CNN Architecture Ablation | Which architectural components matter? | Planned |
| 32 | Transfer Learning vs Training from Scratch | How does pretrained knowledge affect results? | Planned |
| 33 | Data Augmentation Experiment | Which transformations improve generalization? | Planned |
| 34 | Early Stopping Experiment | How does stopping strategy affect results? | Planned |
| 35 | Training Precision Benchmark | What are the speed and memory trade-offs of precision choices? | Planned |
| 36 | Inference Batch Size Benchmark | How does batch size affect throughput and latency? | Planned |

### 🟣 NLP, LLM and RAG Experiments

| No. | Project | Research Question or Skill | Status |
|---|---|---|---|
| 37 | Tokenization Strategy Comparison | How does tokenization affect text processing? | Planned |
| 38 | TF-IDF vs Embedding Search | When does semantic search improve retrieval? | Planned |
| 39 | Embedding Model Benchmark | Which model retrieves relevant passages best? | Planned |
| 40 | Chunk Size Experiment for RAG | How does chunk size affect retrieval quality? | Planned |
| 41 | Chunk Overlap Experiment | Does overlap improve evidence retrieval? | Planned |
| 42 | Top-k Retrieval Experiment | How does retrieval depth affect quality and latency? | Planned |
| 43 | Similarity Metric Comparison | How do cosine and other distance measures compare? | Planned |
| 44 | Reranking Experiment | Does reranking improve relevance? | Planned |
| 45 | Hybrid Search Experiment | How does combining lexical and semantic search perform? | Planned |
| 46 | Prompt Template Comparison | How do instructions affect task quality? | Planned |
| 47 | LLM Temperature Experiment | How does sampling affect variability? | Planned |
| 48 | Structured Output Reliability Experiment | How often do outputs satisfy a required schema? | Planned |
| 49 | RAG Citation Quality Evaluation | Are generated claims supported by sources? | Planned |
| 50 | LLM Hallucination Evaluation | Which task conditions increase unsupported claims? | Planned |
| 51 | LLM Model Comparison | How do models compare on a fixed task-specific dataset? | Planned |
| 52 | LLM Latency and Cost Benchmark | What trade-offs exist between quality, latency, and cost? | Planned |

### 🟠 Research Reproduction and Scientific Practice

| No. | Project | Research Question or Skill | Status |
|---|---|---|---|
| 53 | Research Paper Reading Notes | How can a paper's claims be evaluated critically? | Planned |
| 54 | Published Dataset Baseline Reproduction | Can a reported baseline be reproduced? | Planned |
| 55 | Classical ML Paper Experiment | Can a selected method be implemented and evaluated? | Planned |
| 56 | Neural Network Ablation Study | Which components contribute to performance? | Planned |
| 57 | Hyperparameter Sensitivity Study | Which settings most affect results? | Planned |
| 58 | Small-Scale Paper Reproduction | How closely can results be reproduced with available resources? | Planned |
| 59 | Failed Experiment Analysis | What can unsuccessful runs reveal? | Planned |
| 60 | Research Result Statistical Analysis | How much uncertainty surrounds observed differences? | Planned |

### 🔴 Advanced — Performance, Robustness and Generalization

| No. | Project | Research Question or Skill | Status |
|---|---|---|---|
| 61 | Data Size vs Model Performance | How does more training data affect performance? | Planned |
| 62 | Synthetic vs Real Data Experiment | How does synthetic data affect downstream utility? | Planned |
| 63 | Distribution Shift Experiment | How does performance change on shifted data? | Planned |
| 64 | Noise Robustness Benchmark | How sensitive are models to noisy inputs? | Planned |
| 65 | Model Drift Simulation | How does changing data affect deployed predictions? | Planned |
| 66 | Fairness Metric Trade-off Experiment | How do fairness definitions and performance interact? | Planned |
| 67 | Model Compression Benchmark | How do size, speed, and quality trade off? | Planned |
| 68 | Quantization Experiment | How does lower precision affect inference? | Planned |
| 69 | CPU vs GPU Inference Benchmark | When does hardware choice affect throughput? | Planned |
| 70 | End-to-End Experiment Tracking Framework | Can experiments be reproduced and compared reliably? | Planned |

---

## 📚 Core Concepts Covered

### 1. Scientific Method

- Formulating research questions
- Writing testable hypotheses
- Identifying independent and dependent variables
- Establishing baselines
- Controlling confounding variables
- Defining success criteria before running experiments
- Recording unexpected results
- Distinguishing correlation from causation

### 2. Experimental Design

- Train, validation, and test separation
- Cross-validation
- Controlled comparisons
- Ablation studies
- Sample size considerations
- Repeated trials
- Random seeds
- Confidence intervals
- Avoiding data leakage
- Preventing test-set overfitting

### 3. Model Evaluation

- Selecting appropriate metrics
- Comparing baselines
- Precision, recall, and F1-score
- MAE and RMSE
- Ranking and retrieval metrics
- Calibration
- Error analysis
- Threshold selection
- Generalization
- Evaluation limitations

### 4. Statistical Reasoning

- Mean, median, variance, and standard deviation
- Sampling variability
- Confidence intervals
- Hypothesis testing
- Effect sizes
- Statistical versus practical significance
- Multiple comparisons
- Bootstrap resampling
- Uncertainty in model comparisons

### 5. Deep Learning Experiments

- Architecture choices
- Optimizers and learning rates
- Batch size
- Weight initialization
- Regularization
- Training stability
- Overfitting and underfitting
- Data augmentation
- Compute and memory trade-offs

### 6. LLM and RAG Evaluation

- Prompt sensitivity
- Model variability
- Tokenization
- Embedding quality
- Chunking strategies
- Retrieval metrics
- Reranking
- Grounded answers
- Citation verification
- Hallucination analysis
- Latency and token cost
- Fixed evaluation datasets

### 7. Reproducibility and Experiment Tracking

- Versioning code and data
- Recording environment and dependencies
- Logging parameters and metrics
- Saving model artifacts
- Recording random seeds
- Documenting hardware and runtime
- Keeping experiment histories
- Separating observed results from assumptions

---

## 🗂️ Recommended Project Structure

Use a consistent structure for experiments so another developer can understand and reproduce your work.

```text
19_Research_And_Experiments/
│
├── README.md
│
├── 01_python_vectorization_benchmark/
│   ├── README.md
│   ├── src/
│   ├── experiments/
│   ├── results/
│   └── requirements.txt
│
├── 02_feature_scaling_experiment/
│   ├── README.md
│   ├── notebooks/
│   ├── src/
│   ├── results/
│   └── requirements.txt
│
├── 03_learning_rate_experiment/
│   ├── README.md
│   ├── configs/
│   ├── src/
│   ├── experiments/
│   └── results/
│
├── 04_rag_chunk_size_benchmark/
│   ├── README.md
│   ├── data/
│   ├── configs/
│   ├── src/
│   ├── evaluations/
│   └── results/
│
└── ...
```

### Folder guidelines

- `src/` — reusable implementation code.
- `notebooks/` — exploratory work and visualizations.
- `experiments/` — experiment runners or trial definitions.
- `configs/` — settings and parameter configurations.
- `data/` — permitted datasets or instructions for obtaining them.
- `evaluations/` — evaluation cases and metric definitions.
- `results/` — compact result tables, charts, and summaries.
- `requirements.txt` — dependencies.
- `README.md` — research question, methodology, results, and limitations.

Avoid committing API keys, private datasets, large model weights, or unnecessary generated files.

---

## 🧪 Standard Experiment Workflow

Every substantial experiment should follow this process.

1. **Research question:** State exactly what you want to investigate.
2. **Hypothesis:** Predict what you expect to happen and why.
3. **Baseline:** Define the reference method or existing result.
4. **Dataset:** Record the source, size, preprocessing, and limitations.
5. **Variables:** Identify what changes and what stays fixed.
6. **Methodology:** Define metrics, trial counts, and evaluation conditions.
7. **Implementation:** Write reproducible code and record dependencies.
8. **Execution:** Run the experiment and capture results.
9. **Analysis:** Compare outcomes, variability, and failure cases.
10. **Conclusion:** Explain whether the evidence supports the hypothesis.
11. **Limitations:** Record uncertainty and threats to validity.
12. **Reproduction:** Document how another developer can rerun the experiment.

**Important:** Change one major factor at a time when you want to isolate its effect. More complex interactions may require factorial or other carefully designed experiments.

---

## 📊 Example Experiment Report

### Experiment: Does Feature Scaling Improve Model Performance?

**Research question:** Does standardizing numeric features improve the performance of selected machine learning algorithms?

**Hypothesis:** Standardization may help distance-based and gradient-based methods when features have very different scales. It may have less impact on many tree-based methods.

**Experimental setup:**

1. Select a suitable public dataset.
2. Create fixed training and test partitions.
3. Compare a baseline pipeline with a standardized pipeline.
4. Fit preprocessing only on the training data.
5. Evaluate both approaches using the same data partitions and metrics.
6. Repeat with cross-validation when appropriate.
7. Record scores, runtime, and variation across folds.

**Results table:**

| Model | Preprocessing | Evaluation Metric | Result |
|---|---|---|---|
| Model A | No scaling | To be measured | Pending |
| Model A | Standard scaling | To be measured | Pending |
| Model B | No scaling | To be measured | Pending |
| Model B | Standard scaling | To be measured | Pending |

**Conclusion:** Complete this section only after running the experiment. Explain which models benefited, whether differences were meaningful, and what limitations remain.

---

## 📝 Research Paper Reproduction Template

When reproducing a paper, document:

### 1. Paper Details
- Title
- Authors
- Publication venue and year
- DOI or official paper link

### 2. Research Problem
What problem does the paper investigate?

### 3. Main Contribution
What method or finding does the paper introduce?

### 4. Experimental Setup
- Dataset
- Baseline methods
- Model architecture
- Hyperparameters
- Evaluation metrics

### 5. Reproduction Plan
Which experiments can be reproduced with available data, compute, and time?

### 6. Results
Compare your measured results with the reported results. Include appropriate uncertainty and explain differences.

### 7. Limitations
Document missing details, unavailable resources, implementation differences, and possible sources of variation.

### 8. Conclusion
State what you learned and whether the reproduced evidence supports the paper's main claims.

Do not claim to have reproduced a paper merely because you implemented a similar model. Clearly distinguish a full reproduction from a partial replication or an independent experiment inspired by the paper.

---

## ✅ Experiment Completion Checklist

- [ ] Define a focused research question.
- [ ] State a testable hypothesis.
- [ ] Select a baseline.
- [ ] Document the dataset and permissions.
- [ ] Prevent train-test leakage.
- [ ] Define metrics before evaluating results.
- [ ] Record parameters and environment details.
- [ ] Use appropriate repeated trials or validation.
- [ ] Save results in a reproducible format.
- [ ] Visualize relevant comparisons.
- [ ] Analyze failures and unexpected findings.
- [ ] Discuss uncertainty and practical significance.
- [ ] Document limitations and threats to validity.
- [ ] Include commands or instructions to reproduce the experiment.
- [ ] Commit the code and documentation to GitHub.

---

## 🗺️ Recommended Learning Order

Build your research skills gradually.

### Phase 1 — Learn to Experiment
1. Python Loop vs Vectorization Benchmark
2. Random Seed Reproducibility Lab
3. Sorting Algorithm Benchmark
4. Missing Value Strategy Comparison

### Phase 2 — Compare Machine Learning Methods
5. Feature Scaling Experiment
6. Decision Tree Depth Experiment
7. Cross-Validation Strategy Experiment
8. Learning Curve Analysis

### Phase 3 — Understand Deep Learning
9. Learning Rate Experiment
10. Optimizer Comparison
11. Regularization Comparison
12. Transfer Learning vs Training from Scratch

### Phase 4 — Evaluate Generative AI
13. Embedding Model Benchmark
14. Chunk Size Experiment for RAG
15. Reranking Experiment
16. LLM Model Comparison

### Phase 5 — Develop Research Practice
17. Research Paper Reading Notes
18. Published Dataset Baseline Reproduction
19. Small-Scale Paper Reproduction
20. End-to-End Experiment Tracking Framework

**Recommended strategy:** Start with experiments that run on your computer without a GPU or paid APIs. Build strong measurement and analysis habits before moving to resource-intensive deep learning and LLM experiments.

---

## 📈 Progress Tracker

Update the counts as experiments are implemented and documented.

| Metric | Count |
|---|---:|
| Planned experiments | 70 |
| Completed experiments | 0 |
| Experiments in progress | 0 |
| Experiments with reproducible instructions | 0 |
| Experiments with documented limitations | 0 |
| Paper reproductions completed | 0 |
| Experiments with recorded results | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [Statistics Projects](../06_Statistics_Projects/README.md)
- [EDA and Visualization Projects](../07_EDA_Visualization_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [Testing, Security and Reliability Projects](../16_Testing_Security_Reliability/README.md)
- [Responsible AI Projects](../17_Responsible_AI/README.md)
- [End-to-End Capstones](../18_End_To_End_Capstones/README.md)

---

## 💡 Guiding Principle

**Ask a clear question → Establish a baseline → Design a fair experiment → Measure carefully → Analyze uncertainty → Document honestly → Make evidence-based conclusions.**

The objective is not to prove your original hypothesis right. It is to discover what the evidence actually shows and make your findings reproducible.
