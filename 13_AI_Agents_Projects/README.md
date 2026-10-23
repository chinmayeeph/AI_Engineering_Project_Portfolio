# 🤖 AI Agents Projects

A collection of hands-on projects focused on building AI agents that can use tools, follow workflows, maintain task state, interact with external systems, and solve multi-step problems.

This folder documents my journey from basic tool-calling applications to stateful agent workflows, multi-agent collaboration, and reliable AI agent systems.

> **Current status:** Project ideas and learning roadmap. Projects will be marked as completed as they are implemented, tested, evaluated, and documented.

---

## 🎯 Objectives

- Understand the difference between an LLM application, an AI agent, and a predefined workflow.
- Learn tool calling and function execution.
- Build agents that use Python functions and external APIs.
- Implement task planning and multi-step execution.
- Manage conversation history and agent state.
- Connect agents to document retrieval and knowledge bases.
- Learn workflow orchestration and conditional execution.
- Implement human approval for sensitive actions.
- Evaluate agent correctness, tool selection, and task completion.
- Handle tool errors, retries, timeouts, and unexpected outputs.
- Explore multi-agent collaboration and task delegation.
- Build secure, observable, and maintainable agent applications.

---

## 🧰 Technologies

- **Language:** Python
- **LLM integration:** Provider SDKs and compatible model APIs
- **Agent frameworks:** LangGraph, LangChain, LlamaIndex
- **Validation:** Pydantic
- **API development:** FastAPI
- **Testing:** pytest
- **Data processing:** Pandas, NumPy
- **Knowledge retrieval:** Embeddings, vector search, RAG
- **Database and state:** SQLite, PostgreSQL, suitable checkpoint stores
- **Interface development:** Streamlit
- **Version control:** Git and GitHub
- **Optional local inference:** Ollama or other compatible local models

> **Learning approach:** Begin with ordinary Python functions and a simple LLM tool-calling loop. Learn the control flow yourself before introducing an agent framework.

> **Safety principle:** An agent should not automatically receive unrestricted access to files, terminals, accounts, or external services. Use least-privilege tools, input validation, execution limits, and human approval for consequential actions.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects — Agent Fundamentals

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | Rule-Based Task Assistant | Conditions, functions, task routing | Planned |
| 02 | LLM Tool-Calling Assistant | Tool schemas, function execution | Planned |
| 03 | Calculator Agent | Safe arithmetic tool integration | Planned |
| 04 | Date and Time Assistant | Utility tools, input validation | Planned |
| 05 | Weather Information Agent | API integration, structured results | Planned |
| 06 | Multi-Step Research Planner | Task decomposition, planning | Planned |
| 07 | Web Search Assistant | Search tools, source-based summaries | Planned |
| 08 | Personal Notes Assistant | Read-only file access, retrieval | Planned |
| 09 | Agent Conversation Memory Demo | Conversation history, state | Planned |
| 10 | Agent Error Handling Lab | Tool failures, retries, fallback logic | Planned |

### 🟡 Intermediate Projects — Workflows and Knowledge

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 11 | Research and Report Agent | Search, synthesis, citations | Planned |
| 12 | RAG Knowledge Assistant Agent | Retrieval tools, grounded answers | Planned |
| 13 | Document Analysis Agent | Document parsing, structured findings | Planned |
| 14 | CSV Data Analysis Agent | Data inspection, controlled analysis tools | Planned |
| 15 | SQL Read-Only Analytics Agent | Query generation, validation, database access | Planned |
| 16 | Code Explanation Assistant | Source inspection, explanations | Planned |
| 17 | Python Testing Assistant | Test generation, controlled test execution | Planned |
| 18 | Email Drafting Agent | Context handling, draft generation | Planned |
| 19 | Human-in-the-Loop Approval Agent | Approval gates, state transitions | Planned |
| 20 | Task Tracking Agent | Persistent state, task status | Planned |
| 21 | Conditional Workflow Agent | Branching, routing, deterministic steps | Planned |
| 22 | Agent Workflow with LangGraph | Nodes, edges, state, checkpoints | Planned |
| 23 | API Integration Agent | Tool schemas, API errors | Planned |
| 24 | Agent Evaluation Toolkit | Task success, tool-call accuracy | Planned |

### 🔴 Advanced Projects — Planning and Orchestration

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 25 | Plan-and-Execute Agent | Planning, execution, reassessment | Planned |
| 26 | Reflection and Revision Agent | Critique, revision, verification | Planned |
| 27 | Supervisor and Worker Agents | Delegation, orchestration | Planned |
| 28 | Multi-Agent Research Team | Research roles, evidence synthesis | Planned |
| 29 | Software Development Workflow Agent | Planning, coding assistance, testing | Planned |
| 30 | Data Pipeline Monitoring Agent | Status checks, alerts, recovery suggestions | Planned |
| 31 | Customer Support Triage Agent | Intent routing, knowledge retrieval | Planned |
| 32 | Scheduling Assistant Prototype | Constraints, proposed schedules | Planned |
| 33 | Long-Running Task Agent | Checkpointing, resumable execution | Planned |
| 34 | Parallel Tool Execution Agent | Concurrency, result aggregation | Planned |
| 35 | Agent Memory Comparison Lab | Short-term state, long-term retrieval | Planned |
| 36 | Agent with Structured Output Validation | Schemas, parsing, correction | Planned |

### 🟣 Advanced Extensions — Reliability and Production

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 37 | Agent Observability Dashboard | Traces, latency, errors, tool calls | Planned |
| 38 | Agent Cost and Token Monitor | Usage accounting, budgets | Planned |
| 39 | Agent Security Evaluation Lab | Prompt injection, tool permissions | Planned |
| 40 | Tool Permission and Approval System | Least privilege, human confirmation | Planned |
| 41 | Agent Regression Test Suite | Fixed scenarios, reproducibility | Planned |
| 42 | Agent Benchmarking Framework | Success rate, latency, cost | Planned |
| 43 | Resilient Agent API | FastAPI, timeouts, request validation | Planned |
| 44 | Agent Deployment Prototype | Configuration, deployment, logging | Planned |
| 45 | Multi-Agent Debate and Verification | Independent proposals, evidence checks | Planned |
| 46 | Agent Workflow Replay Tool | Run histories, debugging, reproducibility | Planned |
| 47 | Domain-Specific Operations Agent | Bounded tools, domain constraints | Planned |
| 48 | End-to-End AI Agent Application | Workflow, evaluation, security, deployment | Planned |

---

## 📚 Concepts Covered

### 1. LLM Applications vs. AI Agents

- Ordinary LLM requests and responses
- Tool-calling applications
- Predefined workflows
- Agent-controlled tool selection
- State and context management
- When an agent is unnecessary
- Reliability and cost trade-offs

An agent is not simply a chatbot. In an agentic application, a model may select from permitted tools and participate in a control loop. The surrounding software must still enforce permissions, validate results, and decide when execution ends.

### 2. Tools and Function Calling

- Python functions as tools
- Tool descriptions and schemas
- Function arguments and return values
- Structured outputs
- Tool selection
- Tool execution and result handling
- Validation with Pydantic
- Tool errors and timeouts

### 3. Planning and Execution

- Breaking goals into smaller tasks
- Selecting appropriate tools
- Tracking completed steps
- Conditional execution
- Replanning after failures
- Setting maximum iteration limits
- Detecting loops and repeated actions
- Verifying final results

### 4. Memory and State

- Conversation history
- Working state
- Persistent task state
- Summarized conversation history
- Retrieval-based memory
- Checkpointing
- Resuming interrupted tasks
- Memory relevance and privacy

### 5. Workflow Orchestration

- Sequential workflows
- Conditional branches
- Parallel execution
- Shared state
- Nodes and edges
- Checkpoints
- Human approval steps
- Deterministic execution
- Framework-based orchestration

### 6. Multi-Agent Systems

- Supervisor and worker patterns
- Role-based delegation
- Shared task descriptions
- Independent research
- Result aggregation
- Disagreement resolution
- Agent coordination
- Avoiding unnecessary agent complexity

### 7. Reliability and Evaluation

- Task success rate
- Tool-selection accuracy
- Argument correctness
- Output validation
- Groundedness and factuality
- Retry behavior
- Latency and token usage
- Regression tests
- Trace inspection
- Failure analysis

### 8. Security and Responsible Execution

- Least-privilege tools
- Input and output validation
- Prompt injection risks
- Untrusted tool results
- Human approval for consequential actions
- Read-only access by default
- Secrets and credential management
- Rate limits and execution budgets
- Safe failure behavior
- Protection of sensitive information

### 9. Deployment and Monitoring

- API endpoints
- Request validation
- Configuration management
- Logging and tracing
- Metrics and alerts
- Error reporting
- Model and prompt versioning
- Cost controls
- Automated tests
- Deployment documentation

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
13_AI_Agents_Projects/
│
├── README.md
│
├── 01_llm_tool_calling_assistant/
│   ├── README.md
│   ├── src/
│   │   ├── agent.py
│   │   ├── tools.py
│   │   └── config.py
│   ├── tests/
│   ├── examples/
│   ├── requirements.txt
│   └── .env.example
│
├── 02_research_report_agent/
│   ├── README.md
│   ├── src/
│   ├── tests/
│   ├── evaluations/
│   ├── examples/
│   └── requirements.txt
│
├── 03_rag_knowledge_agent/
│   ├── README.md
│   ├── data/
│   ├── src/
│   ├── tests/
│   ├── evaluations/
│   └── requirements.txt
│
└── ...
```

### Folder guidelines

- `src/` — agent logic, tool implementations, state management, and configuration.
- `tests/` — unit tests, tool tests, and workflow tests.
- `examples/` — safe example inputs and expected outputs.
- `evaluations/` — test scenarios, results, and error analysis.
- `data/` — small permitted sample datasets; never include confidential data.
- `.env.example` — environment variable names with placeholder values only.
- `requirements.txt` — dependencies required to run the project.
- `README.md` — problem statement, architecture, setup, execution, evaluation, and limitations.

For beginner projects, one Python file and a README are sufficient. Add modules and orchestration frameworks when they solve an actual complexity problem.

---

## 🧪 Example: A Basic Agent Execution Loop

A simplified tool-calling agent follows this pattern:

1. Receive a user task.
2. Send the task and permitted tool descriptions to the LLM.
3. Inspect the model's response.
4. If it requests a permitted tool, validate the arguments.
5. Execute the tool and return its result to the model.
6. Continue within a configured step limit.
7. Verify the final answer before returning it.

The model may suggest an action, but **the application controls whether that action is allowed to execute**.

Example safety rules:

- Allow only explicitly registered tools.
- Validate every tool argument.
- Limit the number of execution steps.
- Apply timeouts and error handling.
- Require human confirmation before consequential actions.
- Never use unrestricted code execution as a general-purpose tool.
- Treat external content as untrusted input.

---

## ✅ Project Completion Checklist

- [ ] Define the task and expected outcome.
- [ ] Decide whether an agent is genuinely needed.
- [ ] Define a small set of permitted tools.
- [ ] Document tool inputs, outputs, and permissions.
- [ ] Implement input validation and error handling.
- [ ] Set execution limits and timeouts.
- [ ] Test successful and unsuccessful tool calls.
- [ ] Test missing information and unexpected outputs.
- [ ] Add human approval for sensitive actions.
- [ ] Measure task success and failure rates.
- [ ] Record latency and token usage where available.
- [ ] Add automated tests and reproducible examples.
- [ ] Document security considerations and limitations.
- [ ] Provide setup and execution instructions.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

Follow this sequence to build a solid foundation.

1. **Rule-Based Task Assistant** — practise Python functions and conditions.
2. **LLM Tool-Calling Assistant** — understand tool schemas and execution.
3. **Calculator Agent** — validate arguments and return structured results.
4. **Agent Error Handling Lab** — handle failures and limit execution.
5. **Research and Report Agent** — combine information gathering and synthesis.
6. **RAG Knowledge Assistant Agent** — connect agents to retrieved evidence.
7. **Human-in-the-Loop Approval Agent** — add controlled approval steps.
8. **Conditional Workflow Agent** — implement explicit branching.
9. **Agent Workflow with LangGraph** — learn stateful orchestration.
10. **Agent Evaluation Toolkit** — test behavior systematically.
11. **Supervisor and Worker Agents** — explore multi-agent coordination.
12. **Agent Observability Dashboard** — monitor and debug executions.
13. **End-to-End AI Agent Application** — combine tools, state, evaluation, and deployment.

**Recommendation:** Build one reliable single-agent application before experimenting with multi-agent systems. Multiple agents increase coordination complexity, latency, cost, and the number of possible failure points.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 48 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with automated tests | 0 |
| Projects with documented evaluations | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [Generative AI and RAG Projects](../12_Generative_AI_RAG_Projects/README.md)
- [Backend APIs Projects](../14_Backend_APIs_Projects/README.md)
- [MLOps and Deployment Projects](../15_MLOps_Deployment_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Define the goal → Choose permitted tools → Execute controlled steps → Validate results → Evaluate task completion → Improve reliability.**

The goal is not to make an AI agent act without limits. It is to build useful systems that can complete multi-step tasks while remaining observable, testable, secure, and under appropriate human control.
