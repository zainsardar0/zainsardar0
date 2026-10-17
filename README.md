## Muhammad Zain Ul Abideen

![GitHub stars](https://img.shields.io/github/stars/zainsardar0?style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/zainsardar0?style=for-the-badge)
![Profile views](https://komarev.com/ghpvc/?username=zainsardar0&label=Profile%20views&color=0e75b6&style=for-the-badge)

## Professional Profile

Final-year BS Artificial Intelligence student and AI/ML Engineer building **agentic AI systems** — retrieval-augmented generation, LLM-powered pipelines, and production-grade deployments. I design end-to-end systems where safety is architectural: guardrailed inputs, deterministic citations, and evaluated outputs. Currently focused on agentic RAG, LLMOps, and shipping real products with Docker and CI.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zainsardar0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-zain-ul-abideen-1705032b3/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:zainsardar062@gmail.com)

## Technical Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### AI / Machine Learning

![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-FA1316?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

### Frameworks & Libraries

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

### Data & AI Infrastructure

![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC3262?style=flat-square&logo=qdrant&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Tavily](https://img.shields.io/badge/Tavily-000000?style=flat-square)

### Tools & Deployment

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

## Featured Projects

Building agentic AI systems across healthcare, infrastructure, and education.

---

### 🏥 MedGuide AI — Guardrailed Agentic Medical Q&A

**[View Project Details](https://github.com/zainsardar0/MedGuide-AI)**

Agentic medical assistant that answers health-education questions with grounded, cited, safety-checked responses. A LangGraph agent runs every question through guardrails, retrieval, and output validation — safety checks execute *before* any retrieval spend.

**Key Highlights**

- Guardrail input gate: emergency triage fast-path, greeting handling, and an LLM medical-vs-off-topic classifier that fails open
- Semantic cache: repeat questions answered instantly at cosine ≥ 0.95 with zero API spend
- Deterministic citations: Sources footer appended in code from retrieved evidence — never trusted to the model
- Hybrid retrieval: Pinecone over the *Gale Encyclopedia of Medicine* plus Tavily web fallback
- Streaming SSE answers with clickable source chips, confidence signals, and honest "limited evidence" badges
- 16 keyless CI tests plus a 13-case behavioral eval suite; Dockerized with persistent memory

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[Source Code](https://github.com/zainsardar0/MedGuide-AI)

### ☸️ KubeMind — Enterprise Agentic RAG for Kubernetes

**[View Project Details](https://github.com/zainsardar0/KubeMind)**

Production-grade enterprise Agentic RAG for Kubernetes troubleshooting — an autonomous LangGraph state machine with pre-retrieval security guardrails, two-stage retrieval, and a built-in continuous evaluation suite.

**Key Highlights**

- NVIDIA NeMo Guardrails gate blocks jailbreaks and off-topic queries in <1s before any retrieval spend
- Two-stage retrieval: Qdrant Cloud top-15 → FlashRank cross-encoder rerank to top-5
- Resilient LLM gateway: Portkey with automatic fallback on 429/503
- RAGAS 6-experiment benchmark suite (faithfulness, answer relevancy, context precision/recall) with a Streamlit dashboard
- Full observability via Pydantic Logfire; Docker-hardened deployment

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC3262?style=flat-square&logo=qdrant&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[Source Code](https://github.com/zainsardar0/KubeMind)

### 🎓 EduQuery AI — Prompt-Based Analytics for Academic Databases

**[View Project Details](https://github.com/zainsardar0/EduQuery-AI)**

Prompt-based intelligent analytics and prediction engine for multi-campus academic databases. Educational leaders query institutional data in natural language, receive explainable visualizations, search policy documents via RAG, and review student risk predictions — without exposing confidential student PII.

**Key Highlights**

- Wren AI NL2SQL over 68 governed database definitions across 20 campuses
- Policy Search RAG over institutional documents with exact clause citations
- AutoGluon/TabPFN academic risk engine with SHAP explanations
- sqlglot AST read-only guard plus automatic PII redaction
- React 19 + Vite dashboard with live demo on Vercel

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[Source Code](https://github.com/zainsardar0/EduQuery-AI)

## Certifications

### Stanford University & DeepLearning.AI

- Machine Learning Specialization — 3 courses (Supervised ML, Advanced Learning Algorithms, Unsupervised Learning & Recommenders), instructor Andrew Ng — [View Certificate](https://coursera.org/share/75252557037b773dda07452d73404f5f)

## Activity

![GitHub streak](https://github-readme-streak-stats.herokuapp.com/?user=zainsardar0&theme=github-dark-blue&hide_border=true)

![Activity graph](https://github-readme-activity-graph.vercel.app/graph?username=zainsardar0&bg_color=0d1117&color=58a6ff&line=1f6feb&point=7c3fff&area=true&hide_border=true)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zainsardar0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-zain-ul-abideen-1705032b3/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zainsardar062@gmail.com)

Muhammad Zain Ul Abideen · AI/ML Engineer · Lahore, Pakistan
