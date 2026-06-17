# 👋 Hi, I'm Awais Ahmed

**AI Engineer** building production Generative AI — RAG systems, LLM fine-tuning, and agentic workflows — and taking them from prototype to something a real customer can use.

Currently at **NFON AG**, developing LLM-powered conversational-intelligence features (transcription analysis, summarization, real-time agent assist) for a European cloud-communications platform. Before that, I architected enterprise RAG and fine-tuning systems and ran technical pre-sales at SII Technologies.

I work the full path — model, backend, infrastructure, and the customer conversation. Most of what I build is GDPR / EU AI Act–aware, because that's the reality of shipping AI in Europe.

📍 Ingolstadt, Germany &nbsp;·&nbsp; 🗣 English (C1) · German (B2) · Urdu (native)

---

## 🚀 Featured Projects

### [enterprise-rag](https://github.com/ahmedzahidawais/enterprise-rag) — production RAG for regulated EU clients
Hybrid retrieval (FAISS + BM25) with cross-encoder reranking, a streaming FastAPI backend, and a full **eval harness** — retrieval metrics and answer quality (LLM-as-judge) are measured, not assumed. PII redaction, on-device embeddings, and a Terraform deploy pinned to EU regions. ~$0.25 per 1,000 queries.
`Python · FastAPI · FAISS · BM25 · Cross-encoders · Docker · Terraform · Streamlit`

### [GithubRepoAssistant](https://github.com/ahmedzahidawais/GithubRepoAssistant) — natural-language agent over any GitHub repo
An agent (Pydantic AI) that answers questions about any public repository through 10 tools over the live GitHub REST API — metrics, issues, PRs, commits, contributors, README parsing — with async retries and rate-limit backoff.
`Python · Pydantic AI · GitHub API · async`

### [routed-rag](https://github.com/ahmedzahidawais/routed-rag) — intent-routed RAG chatbot
Routes each query to the right backend — a Chroma-indexed document store or a live weather API — and handles mixed-intent questions across both. Containerized, with a TypeScript frontend.
`Python · FastAPI · LangChain · Chroma · Docker`

**Earlier production work** (internal, no public repo): fine-tuned **Llama-3-8B** (QLoRA / Unsloth) to 98% valid-JSON extraction accuracy and quantized it to GGUF for cost-efficient self-hosted inference; built the FastAPI backend of an automotive recommendation engine — NLP query parsing, VIN detection, real-time API enrichment — from concept to client demo.

---

## 🧰 Tech

**LLM / GenAI** — RAG · agents & tool use · embeddings · cross-encoder reranking · fine-tuning (QLoRA, Unsloth) · LLM evaluation · quantized inference (GGUF, ONNX)

**Languages & Frameworks** — Python · SQL · PyTorch · Transformers · FastAPI · LangChain · LangGraph · Pydantic AI

**Cloud & Infrastructure** — Azure · GCP · AWS · Databricks · Terraform · Docker · CI/CD

**Analytics** — BigQuery · Tableau · Power BI · Looker Studio

---

## 🎓 Certifications

- **Google Cloud Professional Data Engineer** (2025)
- **NVIDIA Certified Associate — Generative AI & LLMs** (NCA-GENL, 2025)

---

## 📫 Connect

- 💼 LinkedIn — https://www.linkedin.com/in/ahmedzahidawais
- ✉️ Email — ahmedzahidawais@gmail.com
