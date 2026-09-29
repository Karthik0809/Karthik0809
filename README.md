<!-- HEADER -->
<h1 align="center">Hi 👋, I'm Karthik Mulugu</h1>
<h3 align="center">AI/ML Engineer @ Socotra | MS in Computer Science @ University at Buffalo</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/karthikmulugu" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin"></a>
  <a href="mailto:karthikmulugu14@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.karthikmulugu.dev" target="_blank"><img src="https://img.shields.io/badge/Portfolio-00C853?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://medium.com/@karthikmulugu" target="_blank"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white"></a>
  <a href="https://doi.org/10.13140/RG.2.2.21211.73766" target="_blank"><img src="https://img.shields.io/badge/Research-4B8BBE?style=for-the-badge&logo=googlescholar&logoColor=white"></a>
</p>

---

## About Me

I build LLM systems that run in production, mostly retrieval pipelines and agents that take real actions. My work sits on one question: **can you trust this model, and how would you know if you couldn't?**

- Focus: retrieval and RAG, agentic systems, evaluation, reliability of deployed AI
- I care about the unglamorous half — evals, failure detection, knowing when a system should abstain instead of guessing
- MS in Computer Science (AI/ML), University at Buffalo · GPA 3.7/4.0

---

## What I'm Working On

**AI/ML Engineer — Socotra (May 2026 – Present)**

Building production AI for insurance software, where the agent acts on real bookings and payments.

- Shipped a production agent on **Amazon Bedrock AgentCore** exposing **51 tools across 12 business domains**
- Hardened the request path with per-request JWT role enforcement, confirmation gates on every state-mutating call, and Bedrock Guardrails against prompt injection
- Built an identity verification service on **AWS Textract** that reads four government ID types and **refuses any field below a 90% confidence threshold** rather than letting unverified data reach the database
- Removed every static credential from our repositories using short-lived OIDC tokens

---

## Research

**DocuQuery: Design, Implementation, and Empirical Analysis of a Hybrid Lexical–Dense Retrieval System with LangGraph Orchestration for PDF Question Answering**
*Under review at IEEE Access* · [Preprint](https://doi.org/10.13140/RG.2.2.21211.73766)

Hybrid BM25 + FAISS retrieval with cross-encoder reranking and a LangGraph verification stage that checks answers against retrieved evidence before returning them.

- **1.00 Recall@5** on paraphrased and multilingual queries
- **73-point recall advantage** over dense-only retrieval under OCR noise, at **37ms median latency**
- Validated with McNemar significance tests and bootstrap confidence intervals rather than a single headline number

The finding I keep using: when BM25 and FAISS disagree about the top passage, that answer is usually the one you shouldn't trust. It's a free failure signal most pipelines compute and throw away.

---

## Previously

**AI Engineer — Pronix Inc. (Oct 2025 – May 2026)**
Designed a production assistant's response-safety layer of input validation, guardrails and hallucination detection, cutting incorrect answers **25%** against a labeled query set. Built and deployed conversational AI on the Kore.ai XO Platform with RAG search and multi-channel delivery.

**AI Engineer Intern — Extern (Jun 2025 – Sep 2025)** · *Top Performer*
Built a RAG pipeline with LangChain, LlamaIndex and FAISS over scanned mortgage documents, raising document-reading accuracy **35%** over keyword search across 1,000 structured documents.

---

## Skills & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Textract-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20CDK-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-FF6F61?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LlamaIndex-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-6A1B9A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI%20Agents-00897B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/NLP-8E44AD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

---

## Quote I Live By

<p align="center"><i>"Machine learning is like money laundering for bias." – Cassie Kozyrkov</i></p>

---
