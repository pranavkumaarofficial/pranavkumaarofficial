<div align="center">

# Pranav Kumaar  
**AI Engineer · Machine Learning Researcher · Production ML Systems**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=800&color=00F7FF&center=true&vCenter=true&width=850&lines=Multi-Agent+LLM+Systems;Production+RAG+%26+Semantic+Search;Local+LLMs+%7C+Quantization+%7C+Inference+at+Scale" />

[![Portfolio](https://img.shields.io/badge/Portfolio-Website-blue?style=flat-square&logo=google-chrome)](https://pranavkumaarofficial.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/pranavkumaarofficial)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:pranavkumaarofficial@gmail.com)

</div>

---

## 🔬 Research & Publications

**ICMLC 2026 (Accepted)**  
**When Graph Structure Hurts: Lightweight Path Ranking for Dense KG-RAG**

- **93.9% AUC** on dense knowledge-graph benchmarks  
- **13× fewer parameters** than GNN-based baselines  
- Designed for **production-scale retrieval**, not toy graphs  

> Focus: efficient reasoning over dense KGs without structural overfitting

---

## 🚀 Selected Systems & Public Projects

### **Channel AI** — Conversational BI via Multi-Agent Orchestration  
🔗 https://github.com/pranavkumaarofficial/newdhatu-enterprise

- Reduced enterprise reporting time **from 2 days → under 30 minutes**
- **Deployed:** 4 enterprise pilots + 12 SMB installations  
- **Latency:** <20s over multi-million-row OLAP datasets  

**Architecture**
- LangGraph-based multi-agent system
- Apache Iceberg analytical data layer
- Specialized agents for intent parsing, semantic reasoning, and execution

**Stack**
`LangGraph` · `OpenAI Agents SDK` · `Apache Iceberg` · `RAG` · `LlamaIndex` · `Qdrant` · `WhatsApp API`

---

### **NLCLI Wizard** — Natural Language → CLI with Local LLMs  
🔗 https://github.com/pranavkumaarofficial/nlcli-wizard

- **83.3% accuracy** on NL → command translation  
- **Runs fully offline** on CPU (810 MB quantized model)  
- ~**1.5s inference**, zero API dependency  

**Technical Highlights**
- Fine-tuned **Gemma 3 1B** using QLoRA  
- GGUF Q4_K_M quantization via llama.cpp  
- Dataset of **1,500 verified command mappings** (all outputs validated)

---

## 🧠 Production Case Studies (No Public Repository)

### **OneSKU** — Hybrid Retrieval for Multi-Vendor Catalog Harmonization

> Implemented as part of a client-facing production system; source code is not publicly releasable.

- **94% precision** on production matching benchmarks  
- <15s query latency across multi-million SKU inventories  
- Deployed across **20+ vendor catalogs**

**System Design Insights**
- Hybrid **BM25 + dense embeddings** outperform purely neural retrieval for noisy catalogs  
- Explicit separation of:
  - **Categorical attributes** → exact-match constraints  
  - **Numerical attributes** → range-aware similarity  
- Custom reconciliation logic for vendor-specific schemas

---

## 🧪 Systems in Progress

- **Efficient Agent Routing for Tool-Heavy LLM Workloads**  
  *Cost-aware agent selection under latency constraints*

- **Small Language Models for Domain-Specific Analytics**  
  *Local inference, quantization, and structured reasoning*

> Repositories and technical write-ups will be published as systems stabilize.

---

## 🛠 Technical Focus Areas

### AI / ML Systems
- Multi-agent LLM architectures (LangGraph)
- Retrieval-Augmented Generation (LlamaIndex, Qdrant, FAISS)
- Fine-tuning & PEFT (QLoRA, Unsloth)
- Model quantization & inference optimization

### Data & Infrastructure
- Apache Iceberg, PostgreSQL
- Vector databases & OLAP optimization
- Docker, Kubernetes
- AWS, Azure, DigitalOcean

### Production Engineering
- FastAPI, Python, TypeScript
- OAuth2, Keycloak, PKI
- HL7 / FHIR healthcare interoperability
- High-availability backend services

---

## 📊 GitHub Snapshot

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pranavkumaarofficial&show_icons=true&theme=radical&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pranavkumaarofficial&layout=compact&theme=radical&hide_border=true" height="150" />
</p>

---

<div align="center">

### 📫 Connect

[Portfolio](https://pranavkumaarofficial.github.io) ·
[LinkedIn](https://linkedin.com/in/pranavkumaarofficial) ·
[Email](mailto:pranavkumaarofficial@gmail.com)

<sub>Interests: multi-agent systems, local LLM deployment, scalable ML infrastructure</sub>

</div>
