# Sarthak Pande

**GenAI Engineer | Multi-Agent Systems · RAG Evaluation · Python Backend Engineering**

I engineer enterprise GenAI workflows across multi-agent orchestration, retrieval systems, document intelligence, and automated presentation generation. My current work at Cognizant focuses on domain-specific conversational AI and RFP/proposal intelligence, with an emphasis on retrieval quality, evaluation, and workflow automation.

[LinkedIn](https://www.linkedin.com/in/sarthak-pande-1435a1229) · [GitHub](https://github.com/sarthakpande108) · [Portfolio](https://github.com/sarthakpande108)

---

## Engineering focus

- **Multi-agent orchestration:** A2A agent integration, LLM-directed sub-agents, MCP tool execution, and domain-specific routing.
- **Retrieval engineering:** HyDE-RAG, hybrid retrieval, BM25, semantic reranking, multi-level document/slide indexes, and relevance-threshold gating.
- **RAG evaluation:** RAGAS evaluation using context precision, context recall, faithfulness, and answer relevancy; regression analysis for retrieval and response quality.
- **LLM-driven document workflows:** Structured extraction, metadata generation, multi-stage summarization, slide planning, and programmatic PPTX generation.
- **AI backend systems:** Python, FastAPI, asynchronous ingestion pipelines, API integration, and cloud deployment workflows.

## Selected engineering work

### Multi-Agent HR Chatbot — Cognizant | GCP

- Owned the HR domain of a multi-domain conversational assistant; implemented the HR A2A agent and integrated it with the root orchestrator.
- Coordinated three LLM-directed sub-agents for policy lookup, HR content retrieval, and recruitment queries.
- Implemented LLM-based keyword selection and tool calling through Liferay MCP servers.
- Combined BM25 retrieval with persona/location filters, Vertex AI semantic reranking, and relevance-score thresholds to gate answer generation.
- Used BigQuery regression analysis to compare response quality across personas and MCP retrieval accuracy; integrated an internal LLM proxy and deployed to GKE lower environments through CloudBees workflows.

### Enterprise RFP / Proposal Intelligence — Cognizant | Azure

- Led a **nine-step asynchronous ingestion and RAG pipeline** using Python, FastAPI, Azure OpenAI, and Azure AI Search.
- Implemented per-slide extraction, structured metadata generation, multi-stage summarization, embeddings, and document-/slide-level indexes.
- Built LLM-driven slide planning to determine slide count, slide type, and content for each RFP.
- Applied **HyDE-based retrieval** across a two-level index to select source slides and rewrite content in proposal style.
- Generated slide-specific PptxGenJS code with Claude and executed it through a Node.js runner.
- Benchmarked baseline RAG against HyDE-RAG using RAGAS metrics and BigQuery-backed regression analysis; reduced proposal preparation time by **up to 80%**.

### AI PowerPoint Design Generator — Cognizant | Azure

- Owned a website-to-template workflow using Playwright to extract client imagery and OpenAI embeddings to retrieve relevant assets and templates.
- Generated branded PPTX design templates and incorporated selected client images programmatically.
- Reduced design turnaround from **days to minutes**.

## Open-source project

### [embedding-drift-lib](https://github.com/sarthakpande108/embedding-drift-lib) · [PyPI](https://pypi.org/project/embedding-drift-lib/)

A lightweight Python library for detecting embedding distribution and coverage shifts in RAG systems, without external services or API keys.

- Uses PCA projection (1,536 dimensions to approximately 50), RBF-kernel Maximum Mean Discrepancy (MMD), per-dimension Wasserstein distance, coverage-gap analysis, and 200-iteration permutation testing.
- Implements severity classification, adaptive sampling, and a drop-in embedding wrapper.
- Diagnoses model drift, query shifts, and stale vector data without requiring changes to an existing RAG pipeline.

## Additional project

### Autonomous Content Agent — [GitHub](https://github.com/sarthakpande108/Linkedin-Automation)

- Built a multi-agent LangGraph workflow with specialized scraping, ranking, writing, and publishing agents.
- Combined LLM-based relevance scoring with heuristic ranking, an email-based human approval gate, and LangSmith tracing.

## Technical skills

| Area | Technologies and methods |
|---|---|
| **Languages** | Python, JavaScript, C++, SQL |
| **LLM frameworks & APIs** | LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, Hugging Face Transformers, OpenAI, Anthropic Claude, Gemini, Azure OpenAI |
| **RAG & retrieval** | HyDE-RAG, Multi-Hop RAG, Hybrid Search, BM25, Semantic Reranking, ChromaDB, FAISS, Pinecone, Azure AI Search |
| **Agents, evaluation & safety** | MCP, A2A, Tool Calling, RAGAS, LLM-as-a-Judge, LangSmith, OpenTelemetry, NeMo Guardrails, Azure AI Content Safety, LoRA/QLoRA |
| **Cloud, backend & DevOps** | FastAPI, Pydantic, GCP, Vertex AI, BigQuery, Azure, AWS (EC2, SNS), Docker, Kubernetes (GKE), CloudBees, GitHub Actions |

## Experience & education

- **AI/ML Engineer — Cognizant Technology Solutions** | Feb 2025 – Present
- **Backend Software Intern — Productry** | Aug 2024 – Feb 2025
- **B.E., Artificial Intelligence & Data Science — Savitribai Phule Pune University** | 2021 – 2025 · CGPA: 8.87/10

**Certifications:** Databricks Certified Generative AI Engineer Associate (2025) · Claude Code Associate (2026)

**Publication:** Co-authored a peer-reviewed paper on *Generative AI for Dynamic Financial Planning and Risk Profiling* (IJERT).

---

[Connect on LinkedIn](https://www.linkedin.com/in/sarthak-pande-1435a1229)
