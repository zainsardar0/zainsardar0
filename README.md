<div align="center">

<h1>Muhammad Zain Ul Abideen</h1>

</div>




<br> 

<div align="center">

<h2>Professional Profile</h2>

</div>

AI/ML Engineer specializing in Computer Vision, Natural Language Processing (NLP), Retrieval-Augmented Generation (RAG), and Multimodal AI. Experienced in building end-to-end machine learning and LLM-powered solutions, optimizing models for production deployment, and developing scalable AI pipelines for applications such as KubeQuery and transformer-based document intelligence.
<p align="center">
  <a href="https://github.com/zainsardar0">
    <img src="https://img.shields.io/badge/GitHub-zainsardar0-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/muhammad-zain-ul-abideen-1705032b3/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:zainsardar062@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<br>

<div align="center">

<h2>Technical Stack</h2>

</div>

### Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

### AI / Machine Learning
<p>
  <img src="https://img.shields.io/badge/LangChain-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/LangGraph-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAGAS-FA1316?style=flat-square"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
</p>

### Frameworks & Libraries
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
</p>

### Data & AI Infrastructure
<p>
  <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white"/>
  <img src="https://img.shields.io/badge/Qdrant-DC3262?style=flat-square&logo=qdrant&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tavily-000000?style=flat-square"/>
</p>

### Tools & Deployment
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
</p>

<div align="center">

<h2>Featured Projects</h2>

</div>

Building agentic AI systems across healthcare, infrastructure, and education.

---

### 🏥 MedGuide AI — Guardrailed Agentic Medical Q&A


Agentic medical assistant that answers health-education questions with grounded, cited, safety-checked responses. A LangGraph agent runs every question through guardrails, retrieval, and output validation — safety checks execute *before* any retrieval spend.

**Key Highlights**
- Guardrail input gate: emergency triage fast-path, greeting handling, and an LLM medical-vs-off-topic classifier that fails open
- Semantic cache: repeat questions answered instantly at cosine ≥ 0.95 with zero API spend
- Deterministic citations: Sources footer appended in code from retrieved evidence — never trusted to the model
- Hybrid retrieval: Pinecone over the *Gale Encyclopedia of Medicine* plus Tavily web fallback
- Streaming SSE answers with clickable source chips, confidence signals, and honest "limited evidence" badges
- 16 keyless CI tests plus a 13-case behavioral eval suite; Dockerized with persistent memory

<p>
<img src="https://img.shields.io/badge/Guardrails-AI--Safety-7c3aed?style=flat"/>
<img src="https://img.shields.io/badge/RAG-Grounded-2ea043?style=flat"/>
<img src="https://img.shields.io/badge/Streaming-SSE-1f6feb?style=flat"/>
<img src="https://img.shields.io/badge/CI-Tested-238636?style=flat"/>
</p>

[Source Code](https://github.com/zainsardar0/MedGuide-AI)


### ☸️ KubeMind — Enterprise Agentic RAG for Kubernetes

<details>
<summary>View Project Details</summary>

Production-grade enterprise Agentic RAG for Kubernetes troubleshooting — an autonomous LangGraph state machine with pre-retrieval security guardrails, two-stage retrieval, and a built-in continuous evaluation suite.

**Key Highlights**
- NVIDIA NeMo Guardrails gate blocks jailbreaks and off-topic queries in <1s before any retrieval spend
- Two-stage retrieval: Qdrant Cloud top-15 → FlashRank cross-encoder rerank to top-5
- Resilient LLM gateway: Portkey with automatic fallback on 429/503
- RAGAS 6-experiment benchmark suite with Streamlit dashboard
- Full observability via Pydantic Logfire; Docker-hardened deployment

<p>
<img src="https://img.shields.io/badge/Agentic-RAG-1f6feb?style=flat"/>
<img src="https://img.shields.io/badge/NeMo-Guardrails-76b900?style=flat"/>
<img src="https://img.shields.io/badge/Reranking-FlashRank-ff7b00?style=flat"/>
<img src="https://img.shields.io/badge/RAGAS-Eval-f85149?style=flat"/>
</p>

</details>

[Source Code](https://github.com/zainsardar0/KubeMind)


### 🎓 EduQuery AI — Prompt-Based Analytics for Academic Databases

<details>
<summary>View Project Details</summary>

Prompt-based intelligent analytics and prediction engine for multi-campus academic databases. Educational leaders query institutional data in natural language, receive explainable visualizations, search policy documents via RAG, and review student risk predictions — without exposing confidential student PII.

**Key Highlights**
- Wren AI NL2SQL over 68 governed database definitions across 20 campuses
- Policy Search RAG over institutional documents with exact clause citations
- AutoGluon/TabPFN academic risk engine with SHAP explanations
- sqlglot AST read-only guard plus automatic PII redaction
- React 19 + Vite dashboard with live demo on Vercel

<p>
<img src="https://img.shields.io/badge/NL2SQL-WrenAI-1f6feb?style=flat"/>
<img src="https://img.shields.io/badge/RAG-Policy--Search-2ea043?style=flat"/>
<img src="https://img.shields.io/badge/SHAP-Explainable-9333ea?style=flat"/>
<img src="https://img.shields.io/badge/PII-Safe-238636?style=flat"/>
</p>

</details>

[Source Code](https://github.com/zainsardar0/EduQuery-AI)

<div align="center">

<h2>Certifications</h2>

</div>

## Core AI & Deep Learning Certifications

### DeepLearning.AI / Stanford University
- Machine Learning Specialization (3 Courses) — [View Certificate](https://coursera.org/share/75252557037b773dda07452d73404f5f)

### DeepEmbed Lab
- Certificate in Artificial Intelligence (CAI)

### Ghulam Ishaq Khan Institute (GIKI)
- Advanced AI Bootcamp (2026)


<br>

<div align="center">

<h2>Activity</h2>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zainsardar0&theme=github-dark-blue&hide_border=true"/>

<br/>



</div>
<br>
<div align="center">


<a href="https://github.com/zainsardar0"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/muhammad-zain-ul-abideen-1705032b3/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
&nbsp;
<a href="mailto:zainsardar062@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br>

<sub>Muhammad Zain Ul Abideen &nbsp;·&nbsp; AI / ML Engineer &nbsp;·&nbsp; Lahore, Pakistan</sub>

<br>

</div>
