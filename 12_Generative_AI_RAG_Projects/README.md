# 🤖 Generative AI & RAG Projects

A collection of hands-on projects focused on building applications powered by Large Language Models (LLMs), prompt engineering, embeddings, vector databases, Retrieval-Augmented Generation (RAG), and LLM evaluation.

This folder documents my journey from fundamental Generative AI concepts to reliable, retrieval-based AI applications and production-oriented LLM systems.

> **Current status:** Project ideas and learning roadmap. Projects will be marked as completed as they are implemented, evaluated, and documented.

---

## 🎯 Objectives

- Understand how Large Language Models work at a practical level.
- Learn prompt engineering and structured output generation.
- Build applications using hosted and locally available language models.
- Understand tokens, context windows, and model limitations.
- Generate and compare text embeddings.
- Learn vector similarity search and vector database fundamentals.
- Build document ingestion and retrieval pipelines.
- Implement Retrieval-Augmented Generation (RAG).
- Evaluate retrieval quality and generated answers separately.
- Reduce hallucinations through evidence-based generation and validation.
- Explore reranking, hybrid search, query transformation, and conversational retrieval.
- Develop, test, and document reusable AI application pipelines.
- Learn the foundations needed for AI agents and production LLM applications.

---

## 🧰 Technologies

- **Language:** Python
- **LLM APIs:** Provider APIs and compatible model endpoints
- **Local models:** Ollama or other supported local inference tools
- **LLM integration:** Direct SDKs, LangChain, LlamaIndex
- **Embeddings:** Sentence Transformers and embedding model APIs
- **Vector search:** FAISS, Chroma, and other compatible vector stores
- **Data processing:** Pandas, NumPy
- **Document processing:** PyMuPDF, python-docx, standard text and Markdown parsers
- **API development:** FastAPI
- **Testing:** pytest
- **Interface development:** Streamlit
- **Version control:** Git and GitHub

> **Learning approach:** Start with direct model calls and simple Python functions. Introduce orchestration frameworks only after understanding prompts, embeddings, retrieval, and model inputs and outputs.

> **Cost and privacy:** Start with free datasets and local experiments where practical. Hosted APIs may charge for usage, and local models require suitable hardware. Never commit API keys, credentials, private documents, or confidential data to GitHub.

---

## 📂 Project Roadmap

Projects are organized from beginner to advanced.

### 🟢 Beginner Projects — LLM Fundamentals

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 01 | First LLM Application | Model calls, inputs, outputs | Planned |
| 02 | Prompt Engineering Playground | Instructions, context, examples | Planned |
| 03 | Text Summarization Assistant | Summarization, output quality | Planned |
| 04 | Structured JSON Generator | Structured outputs, validation | Planned |
| 05 | Email and Message Drafting Assistant | Prompt templates, tone control | Planned |
| 06 | Question Answering with a Fixed Context | Grounded answers, context injection | Planned |
| 07 | LLM Output Evaluation Notebook | Manual evaluation, error analysis | Planned |
| 08 | Token and Context Window Explorer | Tokenization, input limits | Planned |
| 09 | Local LLM Chat Application | Local inference, model configuration | Planned |
| 10 | LLM API Cost Calculator | Token usage, estimated costs | Planned |

### 🟡 Intermediate Projects — Embeddings and RAG

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 11 | Text Embedding Explorer | Dense vectors, embedding models | Planned |
| 12 | Semantic Similarity Search | Vector similarity, cosine similarity | Planned |
| 13 | Personal Notes Search Engine | Document indexing, semantic retrieval | Planned |
| 14 | PDF Question Answering | PDF extraction, chunking, retrieval | Planned |
| 15 | Chat with Your Documents | Ingestion, retrieval, grounded answers | Planned |
| 16 | Company Policy Assistant | Document search, source citations | Planned |
| 17 | Research Paper Assistant | Academic document retrieval | Planned |
| 18 | FAQ Assistant with RAG | FAQ retrieval, response generation | Planned |
| 19 | Markdown Knowledge Base Assistant | File ingestion, incremental indexing | Planned |
| 20 | Multi-Document Comparison Assistant | Cross-document retrieval and synthesis | Planned |
| 21 | RAG with Chroma | Vector storage and similarity search | Planned |
| 22 | RAG with FAISS | Local vector indexing and retrieval | Planned |
| 23 | Conversational RAG Chatbot | Conversation history, contextual queries | Planned |
| 24 | RAG Evaluation Dashboard | Retrieval and answer-quality metrics | Planned |

### 🔴 Advanced Projects — Reliable and Optimized RAG

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 25 | Chunking Strategy Benchmark | Fixed-size, overlap, semantic chunking | Planned |
| 26 | Embedding Model Benchmark | Retrieval quality, latency, resource usage | Planned |
| 27 | Hybrid Search RAG | Keyword and vector search | Planned |
| 28 | Reranking-Based RAG | Candidate retrieval, relevance reranking | Planned |
| 29 | Query Rewriting RAG | Search query transformation | Planned |
| 30 | Multi-Query Retrieval System | Multiple retrieval queries | Planned |
| 31 | Metadata-Aware RAG | Filters, metadata, document attributes | Planned |
| 32 | Context Compression Pipeline | Relevant passage selection | Planned |
| 33 | Citation-Aware Answer Generator | Evidence-linked responses | Planned |
| 34 | RAG Hallucination Evaluation | Grounding, unsupported claims | Planned |
| 35 | Multi-Format Document RAG | PDFs, Markdown, DOCX, text files | Planned |
| 36 | RAG Access-Control Prototype | Document permissions, access isolation | Planned |
| 37 | Incremental Document Indexing | Updates, deletion, index consistency | Planned |
| 38 | RAG Monitoring Dashboard | Latency, failures, retrieval metrics | Planned |
| 39 | RAG Inference API | FastAPI, validation, error handling | Planned |
| 40 | Production-Style RAG Application | Configuration, testing, logging, deployment | Planned |

### 🟣 Advanced Extensions — Beyond Basic RAG

| No. | Project | Learning Focus | Status |
|---|---|---|---|
| 41 | Graph-Enhanced RAG Prototype | Entity relationships, graph retrieval | Planned |
| 42 | Multimodal RAG Prototype | Text and image-containing documents | Planned |
| 43 | Table-Aware Document Question Answering | Table extraction, structured evidence | Planned |
| 44 | Domain-Specific RAG Assistant | Specialized knowledge and evaluation | Planned |
| 45 | RAG Regression Test Suite | Fixed test questions, quality comparisons | Planned |
| 46 | LLM Guardrails Prototype | Input and output validation | Planned |
| 47 | Prompt Injection Defense Lab | Untrusted document and prompt handling | Planned |
| 48 | RAG Benchmarking Framework | Reproducible experiments and comparisons | Planned |

---

## 📚 Concepts Covered

### 1. Large Language Model Fundamentals

- What LLMs do and how text generation works
- Tokens and tokenization
- Context windows
- System and user messages
- Temperature and generation parameters
- Prompt templates
- Few-shot prompting
- Structured outputs
- Model limitations and hallucinations

### 2. Prompt Engineering

- Clear instructions and task definitions
- Context and examples
- Output schemas
- Prompt iteration and versioning
- Separating trusted instructions from untrusted content
- Prompt injection risks
- Evaluating prompt changes against fixed examples

### 3. Embeddings and Vector Search

- Text embeddings
- Dense vector representations
- Cosine similarity and distance measures
- Embedding model selection
- Vector indexing
- Similarity search
- Metadata filtering
- Embedding dimension and storage trade-offs

### 4. Document Ingestion and Chunking

- Loading files
- Extracting text from PDFs and documents
- Cleaning extracted content
- Splitting documents into chunks
- Chunk size and overlap
- Metadata preservation
- Document IDs and source tracking
- Deduplication and incremental updates

### 5. Retrieval-Augmented Generation

A typical RAG pipeline follows this process:

1. Load source documents.
2. Extract and clean their content.
3. Split the content into chunks.
4. Generate embeddings for the chunks.
5. Store the embeddings and metadata.
6. Retrieve relevant chunks for a question.
7. Construct a prompt using the retrieved evidence.
8. Generate an answer using an LLM.
9. Return the answer with source references.
10. Evaluate retrieval quality and answer quality.

**Key distinction:** Retrieval finds potentially relevant evidence. Generation uses that evidence to formulate a response. Both stages must be evaluated.

### 6. Retrieval Optimization

- Keyword search
- Dense vector search
- Hybrid retrieval
- Reranking
- Query rewriting
- Multi-query retrieval
- Metadata filtering
- Context compression
- Retrieval thresholds and abstention

### 7. RAG Evaluation

- Recall@k and Precision@k
- Mean Reciprocal Rank (MRR)
- Normalized Discounted Cumulative Gain (nDCG)
- Context relevance
- Context recall
- Answer correctness
- Faithfulness to retrieved evidence
- Citation correctness
- Latency and cost
- Human review and failure analysis

Metric selection should reflect the application. No single metric proves that a RAG system is reliable.

### 8. Reliability, Security, and Privacy

- Missing or conflicting evidence
- Unsupported answer detection
- Source citations
- Prompt injection through retrieved documents
- Input validation
- Sensitive data handling
- Document-level access controls
- API key management
- Logging without exposing private content
- Graceful failures and safe fallback behavior

### 9. LLM Application Engineering

- Reusable Python modules
- Configuration through environment variables
- API integration
- Automated tests
- Logging and monitoring
- Latency measurement
- Token and cost tracking
- Reproducible evaluation
- Model and prompt versioning
- Deployment considerations

---

## 🗂️ Recommended Project Structure

Each substantial project should have its own folder.

```text
12_Generative_AI_RAG_Projects/
│
├── README.md
│
├── 01_first_llm_application/
│   ├── README.md
│   ├── src/
│   ├── tests/
│   ├── examples/
│   ├── requirements.txt
│   └── .env.example
│
├── 02_prompt_engineering_playground/
│   ├── README.md
│   ├── notebooks/
│   ├── prompts/
│   ├── evaluations/
│   └── requirements.txt
│
├── 03_text_embedding_explorer/
│   ├── README.md
│   ├── notebooks/
│   ├── src/
│   ├── data/
│   └── requirements.txt
│
├── 04_pdf_question_answering/
│   ├── README.md
│   ├── data/
│   ├── src/
│   ├── tests/
│   ├── evaluations/
│   ├── requirements.txt
│   └── .env.example
│
└── ...
```

### Folder guidelines

- `data/` — small sample datasets or instructions to download them; do not commit confidential documents.
- `notebooks/` — experiments and visual explanations.
- `src/` — reusable ingestion, chunking, embedding, retrieval, and generation code.
- `tests/` — tests for parsing, chunking, retrieval, validation, and error handling.
- `prompts/` — versioned prompt templates.
- `evaluations/` — test questions, expected evidence, metrics, and evaluation reports.
- `examples/` — safe sample inputs and outputs.
- `.env.example` — placeholder environment variable names without real credentials.
- `requirements.txt` — project dependencies.

Start small. A beginner project can use one notebook and a README. Add modules, tests, and evaluation files as the application becomes more complex.

---

## 🧪 Recommended Evaluation Dataset

For every RAG project, create a small, manually checked evaluation set.

Example:

| Question | Expected Evidence | Expected Behavior |
|---|---|---|
| What is the refund period? | Policy section describing refunds | Answer with a supporting source |
| Which document describes eligibility? | Eligibility document | Identify the relevant document |
| What is the policy for an unsupported case? | No matching evidence | State that the documents do not provide the answer |
| Two documents give conflicting rules. Which applies? | Both conflicting passages | Identify the conflict instead of inventing a resolution |

Use questions with known answers to compare changes in chunking, embeddings, retrieval settings, reranking, and prompts.

---

## ✅ Project Completion Checklist

- [ ] Define the use case and target users.
- [ ] Identify the model, data source, and expected costs.
- [ ] Document dataset permissions and privacy requirements.
- [ ] Build a simple baseline.
- [ ] Implement document ingestion and text cleaning.
- [ ] Choose and document a chunking strategy.
- [ ] Select an embedding model and retrieval method.
- [ ] Generate answers from retrieved evidence.
- [ ] Return source references where appropriate.
- [ ] Test missing evidence and conflicting information.
- [ ] Evaluate retrieval and answer quality separately.
- [ ] Test malformed inputs and failure cases.
- [ ] Protect API keys and sensitive data.
- [ ] Add automated tests and setup instructions.
- [ ] Document limitations, latency, and estimated costs.
- [ ] Commit the completed project to GitHub.

---

## 🗺️ Recommended Learning Order

Follow this sequence rather than attempting advanced RAG immediately.

1. **First LLM Application** — understand model inputs and outputs.
2. **Prompt Engineering Playground** — experiment with instructions and examples.
3. **Structured JSON Generator** — validate model output.
4. **Text Embedding Explorer** — understand vector representations.
5. **Semantic Similarity Search** — retrieve related text.
6. **PDF Question Answering** — extract, chunk, and retrieve document content.
7. **Chat with Your Documents** — build your first complete RAG pipeline.
8. **RAG Evaluation Dashboard** — measure retrieval and answer quality.
9. **Hybrid Search RAG** — combine keyword and vector retrieval.
10. **Reranking-Based RAG** — improve the relevance of retrieved passages.
11. **Citation-Aware Answer Generator** — connect answers to source evidence.
12. **RAG Inference API** — serve the application through an API.
13. **Production-Style RAG Application** — add tests, monitoring, security, and documentation.

**Important:** You do not need to train an LLM from scratch to build valuable AI engineering projects. Start by understanding how to use existing models, retrieve the right information, evaluate their behavior, and build reliable applications around them.

---

## 📈 Progress Tracker

Update this section as projects are completed.

| Metric | Count |
|---|---:|
| Planned projects | 48 |
| Completed projects | 0 |
| Projects in progress | 0 |
| Projects with documented evaluation | 0 |
| Projects with automated tests | 0 |

---

## 🔗 Related Learning Areas

- [Python Projects](../01_Python_Projects/README.md)
- [NumPy Projects](../03_NumPy_Projects/README.md)
- [Pandas Projects](../04_Pandas_Projects/README.md)
- [Data Engineering Projects](../08_Data_Engineering_Projects/README.md)
- [Machine Learning Projects](../09_Machine_Learning_Projects/README.md)
- [Deep Learning Projects](../10_Deep_Learning_Projects/README.md)
- [NLP Projects](../11_NLP_Projects/README.md)
- [AI Agents Projects](../13_AI_Agents_Projects/README.md)
- [Backend APIs Projects](../14_Backend_APIs_Projects/README.md)
- [MLOps and Deployment Projects](../15_MLOps_Deployment_Projects/README.md)

These links will become useful as the corresponding README files are added to the repository.

---

## 💡 Guiding Principle

**Load trusted data → Prepare documents → Retrieve evidence → Generate an answer → Validate the result → Evaluate quality → Improve reliability.**

The goal is not merely to make an LLM produce an answer. It is to build AI applications that provide useful, evidence-based responses and behave responsibly when the available information is insufficient.
