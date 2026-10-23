# ☁️ Deployment, Cloud & MLOps Projects

A collection of hands-on projects focused on deploying Machine Learning and AI applications, managing model lifecycles, automating workflows, and operating reliable ML systems.

This folder documents my journey from running a model locally to building reproducible, tested, monitored, and cloud-deployed AI/ML applications.

> **Current status:** Project ideas and learning roadmap. Projects will be marked as completed as they are implemented, tested, evaluated, and documented.

---

## 🎯 Objectives

- Understand the complete Machine Learning model lifecycle.
- Package Python applications and ML models for deployment.
- Build prediction APIs using FastAPI.
- Containerize applications using Docker.
- Learn cloud computing and cloud deployment fundamentals.
- Track experiments, parameters, metrics, and model artifacts.
- Manage model versions and promotion between environments.
- Automate testing and deployment with CI/CD.
- Build reproducible data and model pipelines.
- Monitor model performance, latency, and failures.
- Detect data drift and potential model degradation.
- Manage configurations, secrets, and access permissions safely.
- Understand scalable inference and production operations.

---

## 🧰 Technologies

- **Language:** Python
- **ML libraries:** Scikit-learn, Pandas, NumPy
- **API framework:** FastAPI
- **Experiment tracking:** MLflow
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Workflow orchestration:** Prefect or Apache Airflow
- **Cloud platforms:** AWS, Microsoft Azure, Google Cloud
- **Model serving:** FastAPI and compatible model-serving tools
- **Monitoring:** Python logging, Prometheus, Grafana, and cloud-native monitoring services
- **Data and model versioning:** Git, DVC, MLflow
- **Testing:** pytest
- **Infrastructure as code:** Terraform
- **Version control:** Git and GitHub

> **Learning approach:** Start with local deployment and Docker before introducing cloud services. Learn one cloud platform first; the concepts transfer to other providers.

> **Cost awareness:** Many cloud services require billing details or incur charges. Begin with local Docker, free-tier services where eligible, and small datasets. Check current pricing and delete unused resources.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects — Local Deployment

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | Deploy a Scikit-learn Model Locally | Model serialization, inference | Planned |
| 02 | ML Prediction API with FastAPI | REST endpoints, validation | Planned |
| 03 | Model Inference CLI | Command-line prediction workflow | Planned |
| 04 | Batch Prediction Pipeline | CSV input, batch inference | Planned |
| 05 | Model Evaluation Report Generator | Metrics, reproducible reporting | Planned |
| 06 | Model Artifact Versioning Demo | Artifact organization, metadata | Planned |
| 07 | Environment Configuration Demo | Environment variables, settings | Planned |
| 08 | ML Application with Docker | Images, containers | Planned |
| 09 | Dockerized FastAPI Model Service | Containerized model serving | Planned |
| 10 | Health Check and Readiness API | Service health, dependency checks | Planned |

### 🟡 Intermediate Projects — MLOps Foundations

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 11 | ML Experiment Tracking with MLflow | Parameters, metrics, artifacts | Planned |
| 12 | Model Registry Prototype | Model versions, lifecycle stages | Planned |
| 13 | Reproducible Training Pipeline | Configurations, repeatable runs | Planned |
| 14 | Data and Model Versioning with DVC | Dataset and artifact tracking | Planned |
| 15 | Automated ML Testing Pipeline | Unit tests, validation checks | Planned |
| 16 | CI Pipeline with GitHub Actions | Automated checks on commits | Planned |
| 17 | Docker Build and Test Workflow | Image builds, test automation | Planned |
| 18 | Automated Model Evaluation Gate | Metric thresholds, release decisions | Planned |
| 19 | Scheduled Model Retraining Pipeline | Scheduling, repeatable training | Planned |
| 20 | ML Pipeline with Prefect | Tasks, dependencies, retries | Planned |
| 21 | ML Pipeline with Apache Airflow | DAGs, scheduling, task monitoring | Planned |
| 22 | Feature Engineering Pipeline | Reusable transformations | Planned |
| 23 | Model Comparison and Promotion Pipeline | Validation, model selection | Planned |
| 24 | Model Release Documentation Generator | Versions, metrics, release notes | Planned |

### 🔴 Advanced Projects — Cloud Deployment

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 25 | Deploy an ML API to a Cloud Platform | Managed application deployment | Planned |
| 26 | Containerized Cloud Inference Service | Container registry, runtime configuration | Planned |
| 27 | Cloud Object Storage for Model Artifacts | Artifact storage, access permissions | Planned |
| 28 | Cloud-Based Training Pipeline | Training jobs, artifact outputs | Planned |
| 29 | Scheduled Cloud ML Workflow | Scheduling, cloud automation | Planned |
| 30 | Serverless Inference Prototype | Event-driven or serverless execution | Planned |
| 31 | Cloud Secrets Management Demo | Secret storage, access controls | Planned |
| 32 | Managed Database for an ML Application | Database integration, credentials | Planned |
| 33 | Scalable Inference API | Concurrency, capacity planning | Planned |
| 34 | Model Deployment Rollback Demo | Version switching, recovery | Planned |
| 35 | Infrastructure as Code for ML Services | Terraform, repeatable infrastructure | Planned |
| 36 | Cloud Monitoring Dashboard | Logs, metrics, alerts | Planned |

### 🟣 Advanced Projects — Monitoring and Production MLOps

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 37 | ML Service Latency Dashboard | Response times, percentiles | Planned |
| 38 | Data Quality Monitoring Pipeline | Schema, nulls, invalid values | Planned |
| 39 | Data Drift Detection System | Feature distribution changes | Planned |
| 40 | Model Performance Monitoring | Prediction quality, delayed labels | Planned |
| 41 | Model Retraining Trigger Prototype | Monitoring signals, controlled retraining | Planned |
| 42 | Model and Dataset Lineage Tracker | Reproducibility, artifact relationships | Planned |
| 43 | Canary Deployment Simulation | Gradual traffic shifting | Planned |
| 44 | Blue-Green Deployment Prototype | Environment switching, rollback | Planned |
| 45 | Model Inference Load Test | Throughput, resource utilization | Planned |
| 46 | ML Pipeline Failure Recovery Lab | Retries, alerts, idempotency | Planned |
| 47 | LLM Application Observability | Latency, token usage, errors | Planned |
| 48 | End-to-End Production ML System | Training, deployment, monitoring, retraining | Planned |

---

## 📚 Concepts Covered

### 1. Model Packaging and Inference

- Saving and loading trained models
- Serialization and deserialization
- Model input and output schemas
- Batch and online inference
- Feature preprocessing consistency
- Dependency management
- Model artifact metadata
- Reproducible inference
- Model compatibility and versioning

### 2. API Deployment

- FastAPI endpoints
- Request validation
- Response schemas
- Health and readiness checks
- Error handling
- Logging
- Configuration management
- Request timeouts
- API security fundamentals

### 3. Docker and Containers

- Images and containers
- Dockerfiles
- Dependency installation
- Environment variables
- Port mapping
- Container logs
- Persistent storage basics
- Image size optimization
- Reproducible environments
- Container security fundamentals

### 4. Experiment Tracking and Model Management

- Tracking model parameters
- Recording evaluation metrics
- Storing artifacts
- Comparing experiments
- Registering model versions
- Model approval workflows
- Artifact lineage
- Reproducible model selection
- Model release documentation

### 5. CI/CD for ML

- Automated tests
- Code quality checks
- Dependency checks
- Training pipeline validation
- Model evaluation gates
- Docker image builds
- Automated deployment workflows
- Environment-specific configuration
- Release tagging
- Rollback procedures

### 6. Data and Model Pipelines

- Data ingestion
- Data validation
- Feature engineering
- Training and evaluation stages
- Workflow dependencies
- Scheduling
- Retries and timeouts
- Idempotent tasks
- Artifact storage
- Pipeline observability

### 7. Cloud Fundamentals

- Compute, storage, and networking
- Object storage
- Managed databases
- Application deployment services
- Container registries
- IAM and access permissions
- Environment configuration
- Secret management
- Cost monitoring
- Infrastructure as code

### 8. Model Monitoring

- Request counts and failure rates
- Latency percentiles
- Resource utilization
- Data quality checks
- Feature distribution drift
- Prediction distribution monitoring
- Delayed ground-truth labels
- Model performance metrics
- Alert thresholds
- Retraining decisions

**Important:** Data drift does not automatically prove that model performance has degraded. When labels become available, compare actual predictive performance as well.

### 9. Deployment Strategies

- Development, staging, and production environments
- Versioned model releases
- Canary deployment concepts
- Blue-green deployment
- Shadow testing
- Health checks
- Rollback plans
- Release validation

### 10. Production Reliability and Security

- Secrets management
- Least-privilege permissions
- Dependency pinning
- Logging and observability
- Failure recovery
- Backups and retention
- Cost controls
- Privacy-aware telemetry
- Model and data lineage
- Incident documentation

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
15_Deployment_Cloud_MLOps/
│
├── README.md
│
├── 01_local_ml_model_deployment/
│   ├── README.md
│   ├── src/
│   ├── tests/
│   ├── models/
│   ├── requirements.txt
│   └── .gitignore
│
├── 02_fastapi_ml_service/
│   ├── README.md
│   ├── app/
│   │   ├── main.py
│   │   ├── schemas.py
│   │   └── service.py
│   ├── tests/
│   ├── Dockerfile
│   └── requirements.txt
│
├── 03_mlflow_experiment_tracking/
│   ├── README.md
│   ├── src/
│   ├── configs/
│   ├── tests/
│   └── requirements.txt
│
├── 04_data_drift_monitoring/
│   ├── README.md
│   ├── src/
│   ├── data/
│   ├── reports/
│   ├── tests/
│   └── requirements.txt
│
└── ...
```

### Folder guidelines

- `src/` — training, preprocessing, inference, and pipeline code.
- `app/` — API application and service logic.
- `tests/` — unit, integration, and pipeline tests.
- `models/` — local model artifacts when appropriate; avoid committing large or sensitive files.
- `configs/` — non-secret configuration files.
- `data/` — small permitted sample datasets or download instructions.
- `reports/` — evaluation, monitoring, and benchmark outputs.
- `Dockerfile` — instructions for building the container image.
- `.gitignore` — excludes virtual environments, credentials, temporary files, and unwanted artifacts.
- `README.md` — setup, architecture, execution, tests, evaluation, and limitations.

For early projects, a single Python script and a README are enough. Add infrastructure and orchestration files only when the project needs them.

---

## 🧪 Example: An ML Model Release Pipeline

A basic model release workflow can follow these stages:

1. Load a versioned dataset.
2. Validate the data schema and quality.
3. Train the model with recorded configuration.
4. Evaluate the model on a held-out dataset.
5. Compare results with the existing baseline.
6. Run automated tests and acceptance checks.
7. Register or package the approved model.
8. Build and test the serving application.
9. Deploy to a test environment.
10. Verify health checks and sample predictions.
11. Promote the release only after approval.
12. Monitor the deployed service and retain a rollback option.

A failed quality gate should stop promotion rather than silently deploy a worse model.

---

## ✅ Project Completion Checklist

- [ ] Define the model or application and deployment target.
- [ ] Document the runtime and dependency versions.
- [ ] Make training and inference reproducible.
- [ ] Validate input data and model inputs.
- [ ] Save model metadata and evaluation results.
- [ ] Add unit and integration tests.
- [ ] Package the application appropriately.
- [ ] Keep credentials outside source control.
- [ ] Test the deployment in a non-production environment.
- [ ] Add health checks and useful logs.
- [ ] Measure latency and failure rates.
- [ ] Document monitoring and alert thresholds.
- [ ] Define rollback or recovery steps.
- [ ] Estimate cloud costs where applicable.
- [ ] Document limitations and operating instructions.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

Follow this sequence to avoid becoming overwhelmed by cloud tooling.

1. **Deploy a Scikit-learn Model Locally** — learn model loading and prediction.
2. **ML Prediction API with FastAPI** — expose predictions through HTTP.
3. **ML Application with Docker** — package the service.
4. **Automated ML Testing Pipeline** — validate code and predictions.
5. **ML Experiment Tracking with MLflow** — record parameters and results.
6. **Reproducible Training Pipeline** — separate data, training, and evaluation.
7. **CI Pipeline with GitHub Actions** — automate checks on commits.
8. **Data and Model Versioning with DVC** — track artifacts and datasets.
9. **Deploy an ML API to a Cloud Platform** — learn one provider's deployment workflow.
10. **Data Drift Detection System** — monitor changes in input data.
11. **Model Deployment Rollback Demo** — practise safe release management.
12. **End-to-End Production ML System** — combine training, serving, testing, and monitoring.

**Recommendation:** Master local deployment, Docker, automated testing, and experiment tracking before paying for cloud infrastructure. These skills form a strong foundation for cloud-based MLOps.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 48 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with automated tests | 0 |
| Projects with documented deployment steps | 0 |
| Projects with monitoring | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [SQL Projects](../05_SQL_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [AI Agents Projects](../13_AI_Agents_Projects/README.md)
- [Backend APIs Projects](../14_Backend_APIs_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Build → Test → Package → Deploy → Monitor → Evaluate → Improve.**

The goal is not simply to deploy a model once. It is to build reproducible, observable, and maintainable ML systems that can be tested, operated, and improved over time.
