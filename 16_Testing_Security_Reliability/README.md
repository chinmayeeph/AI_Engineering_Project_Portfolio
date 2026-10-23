# 🛡️ Testing, Security & Reliability Projects

A collection of hands-on projects focused on software testing, application security, AI system evaluation, failure handling, and reliability engineering.

This folder documents my journey from writing basic Python tests to validating APIs, securing AI applications, testing LLM behavior, and building dependable software systems.

> **Current status:** Project ideas and learning roadmap. Projects will be marked as completed as they are implemented, tested, evaluated, and documented.

---

## 🎯 Objectives

- Understand why software testing is essential.
- Write unit, integration, and end-to-end tests.
- Use pytest, fixtures, mocks, and parameterized tests.
- Test APIs, databases, and external service integrations.
- Validate input data and handle unexpected errors.
- Identify common application security weaknesses.
- Protect credentials, personal data, and sensitive information.
- Evaluate LLM outputs and RAG retrieval quality.
- Test AI applications for hallucinations, prompt injection, and unsafe behavior.
- Build regression test suites for AI and software applications.
- Measure reliability, latency, failure rates, and recovery behavior.
- Automate quality checks through continuous integration.

---

## 🧰 Technologies

- **Language:** Python
- **Testing:** pytest, unittest, Hypothesis
- **API testing:** FastAPI TestClient, HTTPX
- **Mocking:** unittest.mock, pytest fixtures
- **Code quality:** Ruff, formatting and linting tools
- **Security checks:** Bandit, pip-audit
- **Web application testing:** OWASP ZAP in authorized test environments
- **Performance testing:** Locust
- **Data validation:** Pydantic
- **AI evaluation:** Custom evaluation datasets and task-specific metrics
- **LLM application testing:** Promptfoo or equivalent evaluation tools
- **CI/CD:** GitHub Actions
- **Logging and monitoring:** Python logging and compatible monitoring tools
- **Version control:** Git and GitHub

> **Learning approach:** Start with pytest and ordinary Python programs. Progress to APIs and databases, then add security testing, AI evaluation, and reliability experiments.

> **Security boundary:** Test only applications, systems, accounts, and environments you own or have explicit permission to assess. Use synthetic data and isolated test environments for security exercises.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects — Python Testing Fundamentals

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | Calculator Unit Tests | Assertions, expected results | Planned |
| 02 | BMI Calculator Test Suite | Valid and invalid inputs | Planned |
| 03 | Grade Calculator Test Suite | Boundary conditions | Planned |
| 04 | Fuel Calculator Test Suite | Input validation, edge cases | Planned |
| 05 | String Utility Test Suite | Empty strings, Unicode, whitespace | Planned |
| 06 | Parameterized Testing Lab | Reusing test cases | Planned |
| 07 | Exception Handling Test Suite | Expected errors and exceptions | Planned |
| 08 | Python Mocking Playground | Mock objects, isolated dependencies | Planned |
| 09 | File Processing Test Suite | Temporary files, file errors | Planned |
| 10 | CSV Data Validation Tests | Missing values, invalid records | Planned |

### 🟡 Intermediate Projects — APIs and Application Quality

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 11 | FastAPI Endpoint Test Suite | Requests, responses, status codes | Planned |
| 12 | CRUD API Integration Tests | Create, read, update, delete | Planned |
| 13 | Authentication Test Suite | Login flows, token validation | Planned |
| 14 | Authorization and Role Tests | Access control, ownership checks | Planned |
| 15 | Database Transaction Tests | Rollbacks, consistency | Planned |
| 16 | External API Failure Simulator | Timeouts, unavailable services | Planned |
| 17 | Retry and Backoff Test Lab | Retry limits, recovery behavior | Planned |
| 18 | File Upload Security Tests | File types, sizes, malformed content | Planned |
| 19 | Input Validation Test Suite | Invalid types, boundary values | Planned |
| 20 | Dependency Vulnerability Audit | Dependency scanning, remediation | Planned |
| 21 | Python Static Security Analysis | Unsafe patterns, code review | Planned |
| 22 | Secrets Detection Demo | Preventing credential exposure | Planned |
| 23 | Logging and Error Disclosure Tests | Safe error messages, sensitive data | Planned |
| 24 | Continuous Integration Test Pipeline | Automated tests on code changes | Planned |

### 🔴 Advanced Projects — Security and Reliability

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 25 | Property-Based Testing Lab | Invariants, generated test inputs | Planned |
| 26 | Mutation Testing Experiment | Test-suite effectiveness | Planned |
| 27 | API Rate Limiting Tests | Request limits, abuse resistance | Planned |
| 28 | SQL Injection Prevention Lab | Parameterized queries, safe database access | Planned |
| 29 | Cross-Site Scripting Prevention Lab | Output encoding, safe rendering | Planned |
| 30 | Broken Access Control Test Lab | Resource ownership, permissions | Planned |
| 31 | Security Headers and Configuration Audit | Secure defaults, HTTP headers | Planned |
| 32 | Dependency and Software Bill of Materials Audit | Package inventory, vulnerability review | Planned |
| 33 | Load Testing for a REST API | Throughput, latency, bottlenecks | Planned |
| 34 | Resilience and Fault Injection Lab | Controlled failures, recovery | Planned |
| 35 | Circuit Breaker and Timeout Demo | Failure isolation, bounded waits | Planned |
| 36 | Backup and Recovery Verification | Restoration, data integrity | Planned |

### 🟣 AI-Specific Projects — LLM and ML Reliability

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 37 | ML Prediction Input Validation | Schema checks, invalid features | Planned |
| 38 | ML Model Regression Test Suite | Prediction consistency, metric thresholds | Planned |
| 39 | Dataset Leakage Detection Tests | Train-test separation, leakage checks | Planned |
| 40 | Data Quality Monitoring Tests | Schema drift, missing and invalid values | Planned |
| 41 | LLM Output Schema Validation | Structured responses, parsing failures | Planned |
| 42 | LLM Prompt Regression Tests | Fixed prompts, expected behavior | Planned |
| 43 | RAG Retrieval Quality Test Suite | Recall@k, evidence relevance | Planned |
| 44 | RAG Citation Verification Tests | Evidence-to-answer consistency | Planned |
| 45 | Hallucination and Unsupported Answer Evaluation | Grounding, abstention behavior | Planned |
| 46 | Prompt Injection Defense Evaluation | Untrusted content, instruction separation | Planned |
| 47 | AI Privacy and Sensitive Data Tests | Redaction, data leakage checks | Planned |
| 48 | AI Agent Tool Permission Tests | Tool allowlists, action authorization | Planned |
| 49 | AI Agent Failure Recovery Tests | Tool failures, retry limits | Planned |
| 50 | LLM Latency and Cost Regression Tests | Response time, usage budgets | Planned |
| 51 | AI Safety and Refusal Evaluation | Policy compliance, appropriate refusals | Planned |
| 52 | End-to-End AI Reliability Test Framework | Functional, security, and quality gates | Planned |

---

## 📚 Concepts Covered

### 1. Unit Testing

- Assertions
- Test functions
- Test discovery
- Fixtures
- Parameterized tests
- Setup and teardown
- Exception testing
- Boundary-value analysis
- Test isolation
- Meaningful test names

### 2. Integration and End-to-End Testing

- Testing multiple modules together
- API request and response validation
- Database integration
- Authentication workflows
- External service mocking
- Temporary files and test databases
- End-to-end user workflows
- Test environment configuration

### 3. Test Design and Coverage

- Positive and negative test cases
- Edge cases
- Boundary conditions
- Equivalence partitioning
- Regression testing
- Code coverage
- Mutation testing
- Property-based testing
- Deterministic test data
- Avoiding brittle tests

### 4. Application Security

- Input validation
- Authentication and authorization
- Least-privilege access
- Secure error handling
- SQL injection prevention
- Cross-site scripting prevention
- Secrets management
- Dependency vulnerability checks
- File upload validation
- Security logging
- Rate limiting
- Security misconfiguration

### 5. API Security

- Authentication token validation
- Resource-level permissions
- Request size limits
- Input schema enforcement
- Sensitive error disclosure
- Rate limiting
- Secure configuration
- API key protection
- Audit logging
- Abuse prevention

### 6. Reliability Engineering

- Timeouts
- Retries and backoff
- Circuit breakers
- Graceful degradation
- Failure isolation
- Health checks
- Idempotency
- Recovery testing
- Backups and restoration
- Service-level indicators
- Latency and availability measurement

### 7. Machine Learning Testing

- Input schema validation
- Data quality checks
- Train-test leakage prevention
- Reproducible evaluation
- Prediction sanity checks
- Model regression tests
- Performance thresholds
- Drift monitoring
- Model artifact integrity
- Feature preprocessing consistency

### 8. LLM and RAG Evaluation

- Fixed evaluation datasets
- Prompt regression tests
- Output schema validation
- Retrieval relevance
- Retrieval recall
- Citation verification
- Faithfulness to retrieved evidence
- Unsupported-answer detection
- Refusal behavior
- Latency and token usage
- Human review and error analysis

LLM outputs may vary between runs. Tests should evaluate task-specific requirements and acceptable outcomes rather than assuming every response must match an exact string.

### 9. AI Application Security

- Prompt injection
- Untrusted retrieved content
- Sensitive information disclosure
- Tool authorization
- Excessive agent permissions
- Unsafe output handling
- Data retention and privacy
- Human approval for consequential actions
- Abuse prevention
- Safe failure behavior

### 10. Automated Quality Gates

- Automated test execution
- Code linting
- Static security analysis
- Dependency scanning
- Secret detection
- Model evaluation thresholds
- Build verification
- Deployment approval
- Test reports
- Release regression checks

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
16_Testing_Security_Reliability/
│
├── README.md
│
├── 01_calculator_unit_tests/
│   ├── README.md
│   ├── calculator.py
│   ├── test_calculator.py
│   └── requirements.txt
│
├── 02_fastapi_testing/
│   ├── README.md
│   ├── app/
│   │   └── main.py
│   ├── tests/
│   │   ├── test_routes.py
│   │   └── conftest.py
│   └── requirements.txt
│
├── 03_dependency_security_audit/
│   ├── README.md
│   ├── requirements.txt
│   └── audit_notes.md
│
├── 04_llm_prompt_regression_tests/
│   ├── README.md
│   ├── prompts/
│   ├── evaluations/
│   ├── tests/
│   └── requirements.txt
│
└── ...
```

### Folder guidelines

- `tests/` — automated test cases.
- `app/` or `src/` — the code under test.
- `conftest.py` — shared pytest fixtures.
- `data/` — synthetic or permitted test data.
- `evaluations/` — AI evaluation cases and results.
- `reports/` — coverage, security, or benchmark reports.
- `requirements.txt` — project dependencies.
- `README.md` — purpose, setup, test commands, results, and limitations.
- `.gitignore` — excludes secrets, temporary files, environments, and generated artifacts.

Do not commit real credentials, private datasets, production logs, or sensitive vulnerability details.

---

## 🧪 Example: A Practical Testing Workflow

For a calculator function, a useful test suite should include:

1. Normal addition, subtraction, multiplication, and division.
2. Negative numbers and decimal values.
3. Division by zero.
4. Unexpected input types.
5. Boundary values.
6. A check that invalid input fails in the documented way.

For an AI application, extend the same mindset:

1. Define a representative set of inputs.
2. Document expected behavior and unacceptable outcomes.
3. Run the application against the test set.
4. Measure functional correctness and relevant quality metrics.
5. Inspect failures.
6. Repeat the evaluation after changing prompts, models, or code.

**Key principle:** A passing test suite provides evidence of correctness for the cases tested; it does not prove that a system is completely secure or reliable.

---

## ✅ Project Completion Checklist

- [ ] Define the behavior or security property to test.
- [ ] Identify normal, invalid, and edge-case inputs.
- [ ] Write reproducible test cases.
- [ ] Verify expected success and failure behavior.
- [ ] Isolate external services where appropriate.
- [ ] Test authorization and sensitive-data handling.
- [ ] Add automated tests to the project.
- [ ] Run linting and appropriate security checks.
- [ ] Measure relevant coverage or evaluation metrics.
- [ ] Document discovered issues and fixes.
- [ ] Test recovery from expected failures.
- [ ] Add automated checks to CI where appropriate.
- [ ] Record limitations and remaining risks.
- [ ] Document how another developer can reproduce the tests.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

Follow this sequence to develop testing skills progressively.

1. **Calculator Unit Tests** — learn assertions and pytest.
2. **Fuel Calculator Test Suite** — practise edge cases.
3. **Parameterized Testing Lab** — organize reusable test cases.
4. **Python Mocking Playground** — isolate external dependencies.
5. **FastAPI Endpoint Test Suite** — test HTTP behavior.
6. **CRUD API Integration Tests** — test the application and database together.
7. **Python Static Security Analysis** — identify unsafe coding patterns.
8. **Dependency Vulnerability Audit** — inspect package vulnerabilities.
9. **Continuous Integration Test Pipeline** — automate quality checks.
10. **Load Testing for a REST API** — measure performance under load.
11. **LLM Prompt Regression Tests** — evaluate changes in AI behavior.
12. **RAG Retrieval Quality Test Suite** — assess retrieval quality.
13. **Prompt Injection Defense Evaluation** — test AI-specific security boundaries.
14. **End-to-End AI Reliability Test Framework** — combine functional, security, and AI evaluation.

**Recommendation:** Learn ordinary Python testing before testing complex AI systems. Strong testing fundamentals make it easier to isolate whether a failure comes from your code, data, external service, model, or prompt.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 52 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with automated tests | 0 |
| Projects with security checks | 0 |
| Projects with documented evaluation | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [AI Agents Projects](../13_AI_Agents_Projects/README.md)
- [Backend APIs Projects](../14_Backend_APIs_Projects/README.md)
- [Deployment, Cloud and MLOps Projects](../15_Deployment_Cloud_MLOps/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Define expected behavior → Test normal and edge cases → Check security boundaries → Simulate failures → Measure reliability → Automate regression checks → Improve.**

The goal is not merely to make software pass tests. It is to build AI and software systems that behave predictably, protect users, recover gracefully, and provide measurable evidence of quality.
