# 🧰 Reusable AI Engineering Templates

A collection of reusable templates, starter kits, utilities, configuration files, and engineering workflows designed to accelerate the development of Python, machine learning, Generative AI, RAG, AI agent, API, and MLOps projects.

The purpose of this folder is to build a personal library of reusable components that improve consistency, maintainability, reproducibility, testing, and development speed across projects.

> **Current status:** Template roadmap. Templates will be marked as completed when they are implemented, documented, and verified for reuse.

---

## 🎯 Objectives

- Create reusable Python project structures.
- Build standard templates for scripts, modules, and packages.
- Establish consistent coding and documentation practices.
- Reuse data cleaning and validation utilities.
- Create repeatable machine learning training and evaluation workflows.
- Standardize experiment configuration and tracking.
- Build reusable API, testing, and error-handling components.
- Create templates for LLM, RAG, and AI agent applications.
- Improve configuration and secrets management.
- Standardize logging, monitoring, and deployment.
- Create reusable Responsible AI and security checklists.
- Reduce duplication across portfolio projects.
- Make templates easy to understand, configure, and extend.

---

## 🧰 Technologies and Tools

- **Programming:** Python
- **Data processing:** NumPy, Pandas
- **Machine learning:** Scikit-learn, PyTorch
- **Backend APIs:** FastAPI, Pydantic
- **Testing:** pytest, HTTPX
- **Configuration:** TOML, YAML, JSON, environment variables
- **Code quality:** Ruff, type checking tools
- **Documentation:** Markdown, docstrings
- **Experiment tracking:** MLflow or equivalent tools
- **Containers:** Docker
- **Automation:** GitHub Actions
- **AI applications:** LLM APIs or local models, embeddings, RAG components
- **Version control:** Git and GitHub

Templates should use only the dependencies needed for their intended purpose. Keep beginner templates simple and introduce additional tooling as the use case grows.

---

## 📂 Template Roadmap

### 🟢 Beginner — Python and Project Foundations

| No. | Template | Purpose | Status |
|---|---|---|---|
| 01 | Standard Python Project Structure | Consistent folders for new projects | Planned |
| 02 | Python Script Starter | Main function and entry point | Planned |
| 03 | Python Module Template | Reusable functions and classes | Planned |
| 04 | Python Package Starter | Organize installable Python code | Planned |
| 05 | README Template | Standard project documentation | Planned |
| 06 | `.gitignore` Template | Exclude caches, secrets, and environments | Planned |
| 07 | `requirements.txt` Template | Document project dependencies | Planned |
| 08 | `pyproject.toml` Starter | Central project and tool configuration | Planned |
| 09 | Environment Setup Guide | Reproducible local setup | Planned |
| 10 | Python Logging Starter | Consistent application logs | Planned |
| 11 | Error Handling Template | Consistent exceptions and error messages | Planned |
| 12 | Command-Line Interface Starter | Parse arguments and run tasks | Planned |
| 13 | Configuration Loader | Load and validate settings | Planned |
| 14 | `.env.example` Template | Document required environment variables | Planned |
| 15 | Function Documentation Template | Consistent docstrings and usage examples | Planned |

### 🟡 Intermediate — Data and Machine Learning

| No. | Template | Purpose | Status |
|---|---|---|---|
| 16 | CSV Loading Utility | Read structured data consistently | Planned |
| 17 | Data Cleaning Pipeline | Reusable data preparation steps | Planned |
| 18 | Data Validation Utility | Check schemas, types, and missing values | Planned |
| 19 | Exploratory Data Analysis Notebook | Standard EDA workflow | Planned |
| 20 | Visualization Helper Library | Reusable charts and plot styling | Planned |
| 21 | Feature Engineering Pipeline | Organize repeatable feature transformations | Planned |
| 22 | Train-Test Split Utility | Consistent dataset partitioning | Planned |
| 23 | Scikit-learn Training Pipeline | Preprocessing and model fitting | Planned |
| 24 | Model Evaluation Report | Standard metrics and visualizations | Planned |
| 25 | Classification Metrics Utility | Precision, recall, F1, and confusion matrix | Planned |
| 26 | Regression Metrics Utility | MAE, RMSE, and related measures | Planned |
| 27 | Cross-Validation Template | Repeatable model validation | Planned |
| 28 | Hyperparameter Search Template | Structured model tuning | Planned |
| 29 | Model Serialization Utility | Save and load model artifacts safely | Planned |
| 30 | Prediction Inference Utility | Consistent single-record predictions | Planned |
| 31 | Experiment Configuration Template | Store parameters and experiment settings | Planned |
| 32 | Model Card Template | Document model purpose and limitations | Planned |
| 33 | Dataset Documentation Template | Record data origin and known issues | Planned |
| 34 | Data Quality Report Template | Summarize validation failures and quality | Planned |

### 🔵 Advanced — APIs, Testing, and Engineering

| No. | Template | Purpose | Status |
|---|---|---|---|
| 35 | FastAPI Project Starter | Reusable API structure | Planned |
| 36 | API Route Template | Consistent endpoint organization | Planned |
| 37 | Pydantic Request and Response Schemas | Validate API data | Planned |
| 38 | API Error Response Template | Standardized error handling | Planned |
| 39 | API Authentication Starter | Integrate an appropriate authentication approach | Planned |
| 40 | API Pagination Template | Standard list endpoint pagination | Planned |
| 41 | API Rate Limiting Starter | Apply request limits | Planned |
| 42 | Database Access Layer Template | Separate database operations from business logic | Planned |
| 43 | Database Migration Starter | Manage schema changes | Planned |
| 44 | pytest Test Suite Starter | Organize reusable tests and fixtures | Planned |
| 45 | Mocking and External API Test Utilities | Isolate external dependencies | Planned |
| 46 | API Integration Test Template | Test endpoints and dependencies | Planned |
| 47 | Test Coverage Configuration | Measure code coverage | Planned |
| 48 | Linting and Formatting Configuration | Maintain consistent code quality | Planned |
| 49 | Type Checking Starter | Catch type-related issues | Planned |
| 50 | Security Scanning Workflow | Automate suitable static and dependency checks | Planned |

### 🟣 Generative AI, RAG, and AI Agents

| No. | Template | Purpose | Status |
|---|---|---|---|
| 51 | LLM Application Starter | Reusable model interaction layer | Planned |
| 52 | Prompt Template Library | Organize versioned prompts | Planned |
| 53 | Structured LLM Output Utility | Validate model responses against schemas | Planned |
| 54 | LLM Retry and Timeout Utility | Handle transient failures safely | Planned |
| 55 | Token and Cost Tracking Utility | Estimate and record model usage | Planned |
| 56 | LLM Evaluation Dataset Template | Standardize test examples | Planned |
| 57 | LLM Regression Test Template | Detect behavior changes | Planned |
| 58 | Text Chunking Utility | Prepare documents for retrieval | Planned |
| 59 | Embedding Generation Interface | Standardize embedding operations | Planned |
| 60 | Vector Retrieval Interface | Separate retrieval logic from application code | Planned |
| 61 | RAG Pipeline Starter | Connect ingestion, retrieval, and generation | Planned |
| 62 | RAG Evaluation Report Template | Assess retrieval and answer quality | Planned |
| 63 | Citation Validation Utility | Check references against supplied evidence | Planned |
| 64 | Document Ingestion Pipeline | Process and index supported documents | Planned |
| 65 | AI Agent Tool Interface | Define structured tools and their inputs | Planned |
| 66 | AI Agent Permission Checks | Restrict actions according to explicit permissions | Planned |
| 67 | Human Approval Workflow | Require review before consequential actions | Planned |
| 68 | AI Agent Execution Log | Record steps, errors, and tool calls safely | Planned |
| 69 | AI Safety Evaluation Template | Test selected safety requirements | Planned |
| 70 | AI Application Configuration Starter | Centralize model and runtime settings | Planned |

### 🟠 Deployment, MLOps, and Governance

| No. | Template | Purpose | Status |
|---|---|---|---|
| 71 | Dockerfile Starter | Package an application in a container | Planned |
| 72 | Docker Compose Starter | Run compatible local services together | Planned |
| 73 | GitHub Actions CI Workflow | Automate tests and code checks | Planned |
| 74 | Release Checklist | Standardize release verification | Planned |
| 75 | Model Versioning Template | Track model versions and metadata | Planned |
| 76 | Data Versioning Guide | Track datasets and transformations | Planned |
| 77 | Experiment Tracking Starter | Record parameters, metrics, and artifacts | Planned |
| 78 | Model Monitoring Starter | Track selected prediction and service metrics | Planned |
| 79 | Data Drift Report Template | Summarize changes in incoming data | Planned |
| 80 | Application Health Check Template | Expose service readiness and health | Planned |
| 81 | Structured Logging Configuration | Emit consistent, machine-readable logs | Planned |
| 82 | Monitoring Dashboard Specification | Define operational metrics and alerts | Planned |
| 83 | Backup and Recovery Checklist | Document recovery procedures | Planned |
| 84 | Secrets Management Guide | Keep credentials out of source code | Planned |
| 85 | Responsible AI Risk Assessment Template | Document potential harms and controls | Planned |
| 86 | AI Incident Report Template | Record incidents, impact, and remediation | Planned |
| 87 | Privacy Review Checklist | Review data collection and handling | Planned |
| 88 | Reproducible Experiment Report | Document methodology and measured results | Planned |
| 89 | Architecture Decision Record Template | Explain important design decisions | Planned |
| 90 | End-to-End AI Project Starter Kit | Combine appropriate templates into one starter | Planned |

---

## 📚 Template Design Principles

### 1. Simplicity

- Start with the smallest useful implementation.
- Avoid unnecessary frameworks and dependencies.
- Keep beginner templates easy to read.
- Add complexity only when it solves a real problem.

### 2. Reusability

- Separate configuration from business logic.
- Use clear function and class interfaces.
- Avoid project-specific hardcoded values.
- Provide meaningful defaults where appropriate.
- Make extension points explicit.

### 3. Reliability

- Validate inputs and configuration.
- Handle expected errors deliberately.
- Use timeouts for network operations.
- Add tests for important behavior.
- Document failure modes and limitations.

### 4. Security and Privacy

- Never include real secrets in templates.
- Validate untrusted input.
- Apply least-privilege access.
- Avoid logging passwords, tokens, or sensitive content.
- Use synthetic data in example projects.
- Document required security configuration.

### 5. Reproducibility

- Document dependencies and supported Python versions.
- Provide setup and execution instructions.
- Record relevant model and dataset versions.
- Include sample inputs and expected behavior.
- Explain how to run tests.

### 6. Maintainability

- Follow consistent naming conventions.
- Use docstrings for public functions.
- Keep modules focused.
- Include automated checks where appropriate.
- Document design decisions and known limitations.

---

## 🗂️ Recommended Folder Structure

Organize templates by purpose. Each reusable template should contain the minimum files needed to understand, test, and reuse it.

```text
20_Reusable_Templates/
│
├── README.md
│
├── 01_python_project_template/
│   ├── README.md
│   ├── src/
│   ├── tests/
│   ├── pyproject.toml
│   └── .gitignore
│
├── 02_data_pipeline_template/
│   ├── README.md
│   ├── src/
│   ├── tests/
│   ├── config/
│   └── requirements.txt
│
├── 03_ml_project_template/
│   ├── README.md
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   ├── tests/
│   ├── configs/
│   └── requirements.txt
│
├── 04_fastapi_template/
│   ├── README.md
│   ├── app/
│   ├── tests/
│   ├── pyproject.toml
│   └── Dockerfile
│
├── 05_rag_application_template/
│   ├── README.md
│   ├── ingestion/
│   ├── retrieval/
│   ├── generation/
│   ├── evaluations/
│   └── tests/
│
├── 06_ai_agent_template/
│   ├── README.md
│   ├── tools/
│   ├── workflows/
│   ├── tests/
│   └── config/
│
└── ...
```

---

## 🧪 Example: Standard Python Project Starter

A minimal Python application can use the following structure:

```text
my_python_project/
├── README.md
├── pyproject.toml
├── .gitignore
├── src/
│   └── my_project/
│       ├── __init__.py
│       └── main.py
└── tests/
    └── test_main.py
```

Example implementation:

```python
def add_numbers(a: float, b: float) -> float:
    """Return the sum of two numbers."""
    return a + b


def main() -> None:
    """Run the application."""
    print(add_numbers(10, 20))


if __name__ == "__main__":
    main()
```

Example test:

```python
from my_project.main import add_numbers


def test_add_numbers():
    assert add_numbers(10, 20) == 30


def test_add_numbers_with_negative_values():
    assert add_numbers(-5, 2) == -3
```

The exact package layout and import configuration may need adjustment based on how the project is installed or executed. A reusable template should include setup instructions that make these imports work reliably.

---

## 🧪 Template Validation Checklist

Before marking a template as reusable:

- [ ] Create a clear README explaining its purpose.
- [ ] Document prerequisites and dependencies.
- [ ] Provide setup instructions.
- [ ] Include a minimal working example.
- [ ] Add tests for important behavior.
- [ ] Verify the template in a fresh environment.
- [ ] Remove hardcoded personal paths and credentials.
- [ ] Add a suitable `.gitignore`.
- [ ] Validate configuration and error handling.
- [ ] Document security considerations.
- [ ] Explain customization points.
- [ ] Record known limitations.
- [ ] Verify that another project can reuse it.
- [ ] Commit the tested template to GitHub.

---

## 🗺️ Recommended Learning Order

Build the reusable toolkit gradually rather than creating all 90 templates immediately.

### Phase 1 — Python Foundations
1. Standard Python Project Structure
2. Python Script Starter
3. README Template
4. `.gitignore` Template
5. Python Logging Starter

### Phase 2 — Data and Machine Learning
6. CSV Loading Utility
7. Data Validation Utility
8. Scikit-learn Training Pipeline
9. Model Evaluation Report
10. Experiment Configuration Template

### Phase 3 — Testing and APIs
11. pytest Test Suite Starter
12. FastAPI Project Starter
13. Pydantic Request and Response Schemas
14. API Integration Test Template
15. Security Scanning Workflow

### Phase 4 — Generative AI
16. Prompt Template Library
17. Structured LLM Output Utility
18. RAG Pipeline Starter
19. LLM Regression Test Template
20. AI Agent Permission Checks

### Phase 5 — Production Engineering
21. GitHub Actions CI Workflow
22. Dockerfile Starter
23. Model Monitoring Starter
24. Secrets Management Guide
25. End-to-End AI Project Starter Kit

**Recommended strategy:** Every time you finish a project in another portfolio category, identify one piece of code or documentation that could be reused. Extract it into a template, write tests, and validate it with a second project.

---

## 📈 Progress Tracker

Update this section as templates are implemented and verified.

| Metric | Count |
|---|---:|
| Planned templates | 90 |
| Completed templates | 0 |
| Templates in progress | 0 |
| Templates with automated tests | 0 |
| Templates verified in a fresh environment | 0 |
| Templates with setup documentation | 0 |
| Templates reused by another project | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [AI Agents Projects](../13_AI_Agents_Projects/README.md)
- [Backend APIs Projects](../14_Backend_APIs_Projects/README.md)
- [Deployment, Cloud and MLOps Projects](../15_Deployment_Cloud_MLOps/README.md)
- [Testing, Security and Reliability Projects](../16_Testing_Security_Reliability/README.md)
- [Responsible AI Projects](../17_Responsible_AI/README.md)
- [End-to-End Capstones](../18_End_To_End_Capstones/README.md)
- [Research and Experiments](../19_Research_And_Experiments/README.md)

---

## 💡 Guiding Principle

**Build once → Test thoroughly → Document clearly → Reuse confidently → Improve continuously.**

A good template is more than a folder of starter code. It is a tested, understandable, secure, and reproducible foundation that makes the next engineering project easier.
