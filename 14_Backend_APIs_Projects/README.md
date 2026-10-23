# ⚙️ Backend APIs Projects

A collection of hands-on projects focused on building backend applications, REST APIs, database-connected services, and production-oriented endpoints using Python.

This folder documents my journey from basic HTTP concepts and API development to serving Machine Learning models, Generative AI applications, and AI-powered services through reliable backend systems.

> **Current status:** Project ideas and learning roadmap. Projects will be marked as completed as they are implemented, tested, and documented.

---

## 🎯 Objectives

- Understand HTTP, REST APIs, requests, and responses.
- Build backend applications using Python and FastAPI.
- Design endpoints with appropriate methods and status codes.
- Validate incoming requests and outgoing responses.
- Handle errors and invalid inputs consistently.
- Integrate APIs with SQL databases.
- Implement authentication and authorization fundamentals.
- Write automated tests for API endpoints.
- Learn pagination, filtering, sorting, and API versioning.
- Connect backend services to Machine Learning and LLM applications.
- Handle logging, configuration, timeouts, and rate limits.
- Understand deployment, monitoring, and API documentation.

---

## 🧰 Technologies

- **Language:** Python
- **Backend framework:** FastAPI
- **Alternative framework:** Flask
- **API client:** Requests and HTTPX
- **Data validation:** Pydantic
- **Database:** SQLite, PostgreSQL
- **ORM:** SQLAlchemy
- **Database migrations:** Alembic
- **Testing:** pytest, FastAPI TestClient
- **API documentation:** OpenAPI, Swagger UI
- **Authentication:** OAuth 2.0 concepts, JWT-based authentication where appropriate
- **Server:** Uvicorn
- **Containerization:** Docker
- **Version control:** Git and GitHub

> **Learning approach:** Start with FastAPI, Python functions, and Pydantic. Add databases, authentication, Docker, and deployment after understanding the basics.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects — API Fundamentals

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | Hello World API | First endpoint, FastAPI, Uvicorn | Planned |
| 02 | Calculator API | Query parameters, request handling | Planned |
| 03 | BMI Calculator API | Input validation, numeric responses | Planned |
| 04 | Grade Calculator API | Conditional logic, JSON responses | Planned |
| 05 | Unit Conversion API | Reusable functions, validation | Planned |
| 06 | To-Do List API | CRUD operations, in-memory storage | Planned |
| 07 | Notes Management API | Path parameters, request bodies | Planned |
| 08 | Student Records API | Pydantic schemas, data validation | Planned |
| 09 | Product Catalog API | Filtering, sorting, pagination | Planned |
| 10 | HTTP Status Code Explorer | Methods, status codes, error responses | Planned |

### 🟡 Intermediate Projects — Databases and Application Logic

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 11 | Expense Tracker API | CRUD, SQLite integration | Planned |
| 12 | Employee Management API | Database models, validation | Planned |
| 13 | Library Management API | Relationships, business rules | Planned |
| 14 | Blog Platform API | Users, posts, comments | Planned |
| 15 | Inventory Management API | Stock updates, validation | Planned |
| 16 | Job Listings API | Search, filtering, pagination | Planned |
| 17 | Authentication API | Login, password hashing, token handling | Planned |
| 18 | Role-Based Access API | Authorization, access permissions | Planned |
| 19 | File Upload API | File validation, storage | Planned |
| 20 | Image Metadata API | File processing, structured output | Planned |
| 21 | External API Integration Service | HTTPX, timeouts, error handling | Planned |
| 22 | API Rate Limiting Demo | Request limits, abuse prevention | Planned |
| 23 | API Versioning Demo | Versioned routes, compatibility | Planned |
| 24 | Automated API Testing Suite | pytest, test clients, fixtures | Planned |

### 🔴 Advanced Projects — Production-Oriented APIs

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 25 | PostgreSQL-Based REST API | Relational storage, SQLAlchemy | Planned |
| 26 | Database Migration Pipeline | Alembic, schema evolution | Planned |
| 27 | Background Task API | Asynchronous tasks, status tracking | Planned |
| 28 | Async External API Aggregator | Async I/O, concurrent requests | Planned |
| 29 | Caching API | Cache keys, expiration, invalidation | Planned |
| 30 | Webhook Receiver Service | Event validation, retries | Planned |
| 31 | API Logging and Monitoring Service | Structured logs, request metrics | Planned |
| 32 | Centralized Error Handling API | Consistent errors, exception handlers | Planned |
| 33 | Dockerized FastAPI Application | Containers, configuration | Planned |
| 34 | CI Testing Pipeline for an API | Automated tests, GitHub Actions | Planned |
| 35 | Secure File Processing API | Validation, size limits, safe storage | Planned |
| 36 | API Performance Benchmark | Latency, throughput, bottleneck analysis | Planned |

### 🟣 AI Engineering APIs — Model Serving and AI Integration

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 37 | Machine Learning Prediction API | Model loading, prediction endpoint | Planned |
| 38 | Batch Prediction API | Batch inputs, output validation | Planned |
| 39 | Model Comparison API | Multiple models, consistent schemas | Planned |
| 40 | Text Classification API | NLP inference, label probabilities | Planned |
| 41 | Sentiment Analysis API | Text inputs, classification results | Planned |
| 42 | Embedding Generation API | Vector generation, batching | Planned |
| 43 | Semantic Search API | Embeddings, similarity retrieval | Planned |
| 44 | RAG Question Answering API | Retrieval, LLM response generation | Planned |
| 45 | LLM Chat API | Conversation state, model integration | Planned |
| 46 | AI Agent Execution API | Tool orchestration, execution limits | Planned |
| 47 | AI Usage and Cost Tracking API | Token usage, request accounting | Planned |
| 48 | End-to-End AI Service | API, database, model, tests, deployment | Planned |

---

## 📚 Concepts Covered

### 1. HTTP and REST Fundamentals

- Client-server architecture
- HTTP requests and responses
- GET, POST, PUT, PATCH, and DELETE
- Path and query parameters
- Request bodies and JSON
- HTTP status codes
- Headers and content types
- REST resource design
- Idempotency and safe operations

### 2. FastAPI Fundamentals

- Application creation
- Route definitions
- Path operations
- Pydantic request models
- Response models
- Dependency injection
- Automatic OpenAPI documentation
- Swagger UI
- Environment-based configuration
- Reusable routers

### 3. Input Validation and Error Handling

- Required and optional fields
- Type validation
- Range constraints
- Custom validation rules
- Consistent error responses
- Exception handlers
- Invalid JSON handling
- Defensive programming
- Safe error messages

### 4. Database Integration

- SQLite and PostgreSQL
- SQL fundamentals
- SQLAlchemy models
- Database sessions
- CRUD operations
- Primary and foreign keys
- Relationships and constraints
- Transactions
- Database migrations
- Connection and session management

### 5. Authentication and Authorization

- Authentication versus authorization
- Password hashing
- Token-based authentication
- JWT concepts
- OAuth 2.0 fundamentals
- Role-based access control
- Resource ownership checks
- Secret management
- Rate limiting
- Protecting sensitive endpoints

### 6. API Testing

- Unit tests
- Integration tests
- FastAPI TestClient
- HTTPX
- Test fixtures
- Mocking external services
- Database test isolation
- Authentication tests
- Error-path testing
- Regression testing

### 7. Performance and Reliability

- Synchronous versus asynchronous I/O
- Async HTTP requests
- Timeouts and retries
- Pagination
- Caching
- Background processing
- Logging and metrics
- Connection pooling
- Load testing
- Graceful error handling

### 8. AI and Machine Learning Model Serving

- Loading saved models
- Input feature validation
- Prediction endpoints
- Batch inference
- Output serialization
- Model versioning
- Inference latency
- Model resource management
- Request size limits
- Error handling for model failures

### 9. LLM and RAG Integration

- LLM API integration
- Embedding endpoints
- Semantic search
- RAG retrieval and generation
- Conversation management
- Token and usage tracking
- Streaming responses
- Timeouts and provider failures
- Output validation
- Protecting credentials and user data

### 10. Deployment Fundamentals

- Environment variables
- Dependency management
- Docker basics
- Production server configuration
- Health-check endpoints
- CI pipelines
- Logging and monitoring
- Deployment configuration
- API documentation
- Secure handling of secrets

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
14_Backend_APIs_Projects/
│
├── README.md
│
├── 01_hello_world_api/
│   ├── README.md
│   ├── main.py
│   └── requirements.txt
│
├── 02_todo_list_api/
│   ├── README.md
│   ├── app/
│   │   ├── main.py
│   │   ├── schemas.py
│   │   ├── routes.py
│   │   └── services.py
│   ├── tests/
│   └── requirements.txt
│
├── 03_expense_tracker_api/
│   ├── README.md
│   ├── app/
│   │   ├── main.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   ├── database.py
│   │   └── routes/
│   ├── tests/
│   ├── requirements.txt
│   └── .env.example
│
└── ...
```

### Folder guidelines

- `app/` — application code.
- `routes/` — endpoint definitions.
- `schemas.py` — request and response validation models.
- `models.py` — database models.
- `database.py` — database configuration and sessions.
- `services.py` — reusable business logic.
- `tests/` — unit and integration tests.
- `requirements.txt` — project dependencies.
- `.env.example` — placeholder environment variable names.
- `README.md` — setup, endpoint examples, architecture, tests, and limitations.

For beginner projects, a single `main.py` file is enough. Introduce a multi-file structure as the application grows.

---

## 🧪 Example API Design

A simple student records API might expose these endpoints:

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/students` | List student records |
| GET | `/students/{student_id}` | Retrieve one student |
| POST | `/students` | Create a student |
| PATCH | `/students/{student_id}` | Update selected fields |
| DELETE | `/students/{student_id}` | Delete a student |
| GET | `/health` | Check service health |

Each endpoint should validate its inputs, return appropriate status codes, and handle missing records consistently.

For database-backed endpoints, add pagination and ensure users can access only the records they are authorized to view or modify.

---

## ✅ Project Completion Checklist

- [ ] Define the API's purpose and expected users.
- [ ] Document endpoints and HTTP methods.
- [ ] Define request and response schemas.
- [ ] Validate incoming data.
- [ ] Return appropriate HTTP status codes.
- [ ] Implement error handling.
- [ ] Integrate a database if required.
- [ ] Protect credentials and sensitive information.
- [ ] Implement authentication when required.
- [ ] Add unit and integration tests.
- [ ] Test invalid inputs and missing resources.
- [ ] Configure timeouts for external dependencies.
- [ ] Add logging and a health-check endpoint.
- [ ] Document setup and example requests.
- [ ] Verify the application can run from a clean setup.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

Follow this progression rather than starting with a complex production application.

1. **Hello World API** — create and run your first FastAPI app.
2. **Calculator API** — learn request parameters and responses.
3. **To-Do List API** — implement CRUD operations.
4. **Student Records API** — practise Pydantic validation.
5. **Expense Tracker API** — introduce SQLite and SQLAlchemy.
6. **Automated API Testing Suite** — test successful and failed requests.
7. **Authentication API** — learn password hashing and token handling.
8. **PostgreSQL-Based REST API** — build a database-backed service.
9. **Machine Learning Prediction API** — serve a trained model.
10. **Embedding Generation API** — expose an NLP capability.
11. **RAG Question Answering API** — connect retrieval and LLM inference.
12. **Dockerized FastAPI Application** — package the application.
13. **End-to-End AI Service** — combine API, database, tests, and deployment.

**Recommendation:** Build and test ordinary REST APIs before adding AI. This helps separate backend bugs from model or prompt problems when you later build AI-powered services.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 48 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with automated tests | 0 |
| Projects with documented API endpoints | 0 |
| AI model-serving projects completed | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [DSA Projects](../02_DSA_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [SQL Projects](../05_SQL_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [AI Agents Projects](../13_AI_Agents_Projects/README.md)
- [MLOps and Deployment Projects](../15_MLOps_Deployment_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Receive a request → Validate the input → Execute business logic → Access data or a model → Return a structured response → Test and monitor the service.**

The goal is not merely to create endpoints. It is to build maintainable, secure, well-tested backend services that make software and AI capabilities usable by other applications.
