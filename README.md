<h1 align="center">Hi 👋 I'm Nitin</h1>
<p align="center">
  <b>AI Engineer | LLM Agents · Evals & Guardrails · RAG</b><br>
  <b>MS in Artificial Intelligence @ Northeastern University &nbsp;|&nbsp; Founder @ AgentSentinel</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nitin-k-g"><img src="https://img.shields.io/badge/LinkedIn-nitin--k--g-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nitingoyal3150@gmail.com"><img src="https://img.shields.io/badge/Email-nitingoyal3150@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="https://pypi.org/project/agentsentinel-ai/"><img src="https://img.shields.io/pypi/v/agentsentinel-ai?label=agentsentinel-ai&color=blue"/></a>
</p>

---

## 🚀 About Me

I build AI systems that work in production — not just in notebooks.

- 🛡️ Founder of **[AgentSentinel](https://github.com/nitin3150/agentsentinel)** — open-source LLM agent governance platform (evals, guardrails, adversarial testing) · `pip install agentsentinel-ai`
- 🔬 Focused on **LLM evaluation, runtime guardrails, RAG pipelines, and multi-agent orchestration**
- 🏥 Shipped agentic AI in **HIPAA-compliant healthcare environments** — cut document review from 48h → 6h, reduced hallucination rates by 40%
- ⚡ Prior background in **distributed ML systems** — Kafka, Spark, Airflow, anomaly detection at 1M+ records/day

📫 Open to **AI Engineer** roles in healthcare AI, developer tooling, or high-stakes automation where reliability actually matters.

📄 [View My Resume](https://drive.google.com/file/d/15IKbcXn0ujQWfraK215T3q3aUmV3JDNz/view?usp=sharing)

---

## 🛠️ Tech Stack

**AI / ML**

![LangGraph](https://img.shields.io/badge/LangGraph-0A66C2?style=flat&logo=graphql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=chainlink&logoColor=white)
![DSPy](https://img.shields.io/badge/DSPy-6A0DAD?style=flat&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-FF6B6B?style=flat&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-00C49F?style=flat&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-FF9900?style=flat&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-7C3AED?style=flat&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

> LLM Evals · Guardrails · RAG Pipelines · Prompt Engineering · Adversarial Testing · Multi-Agent Systems

**Backend / Infra**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)

**Databases**

![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

---

## 🔬 Projects

### 🛡️ AgentSentinel — LLM Agent Governance & Safety Platform

[![PyPI](https://img.shields.io/pypi/v/agentsentinel-ai?color=blue&label=PyPI)](https://pypi.org/project/agentsentinel-ai/)
[![GitHub](https://img.shields.io/github/stars/nitin3150/agentsentinel?style=social)](https://github.com/nitin3150/agentsentinel)

Open-source platform to **inspect, stress-test, and optimize LLM agents** before production deployment. Built for teams that can't afford to find out their agent is broken in production.

- **3-stage pipeline:** Inspect → Stress-Test → Optimize using LangGraph orchestration + DSPy prompt rewriting
- **7 concurrent analyzers** covering prompt injection, tool quality, memory leakage, persona drift, and hallucination risk
- **100 adversarial prompts per run** across HIPAA / SOC2 / OWASP LLM Top 10 compliance rule sets
- **Provider-agnostic** via LiteLLM — 100+ LLM providers, zero code changes
- Improved agent pass rate from **60% → 85%** across adversarial test runs

```bash
pip install agentsentinel-ai
```

---

### 🏆 Saddle — Self-Improving Multi-Agent Orchestration Harness

[![GitHub](https://img.shields.io/badge/GitHub-saddle-black?style=flat&logo=github)](https://github.com/nitin3150/saddle)
![Award](https://img.shields.io/badge/🏆_Best_Use_of_Weave-Multi--Agent_Hackathon-gold?style=flat)

Self-improving harness that **autonomously diagnoses inter-agent coordination failures** and rewires team topology without human intervention.

- Lifted correctness **65% → 92%** and multi-hop retrieval accuracy **36% → 93%** across 4 optimization generations
- **5 Weave-instrumented coordination scorers** (correctness, retrieval recall, redundancy, verifier override, token cost)
- One-change-per-generation optimizer with **automatic regression detection and rollback**
- Built with LangGraph, DSPy, W&B Weave

---

### 🏥 Progress Note Understanding — Clinical Reasoning with LLMs

- Fine-tuned **BERT & ClinicalBERT** for clinical note classification across healthcare document types
- Applied **knowledge distillation** to reduce model size by 60% while retaining 95% of performance
- Focused on responsible AI practices for high-stakes medical NLP

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nitin--k--g-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitin-k-g)
[![Email](https://img.shields.io/badge/Email-nitingoyal3150%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:nitingoyal3150@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-nitin3150-181717?style=flat&logo=github&logoColor=white)](https://github.com/nitin3150)

---

💡 *I care about the unglamorous parts — evaluation, latency, hallucination mitigation, the things that separate a demo from a system you'd actually trust.*
