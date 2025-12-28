<div align="center">

# Pranav Kumaar  
**AI Engineer · Machine Learning Researcher · Production ML Systems**

I design and deploy **AI systems that survive real-world constraints** — from multi-agent LLM architectures and retrieval pipelines to cost-aware local inference used in production environments.

[![Portfolio](https://img.shields.io/badge/Portfolio-Website-blue?style=flat-square&logo=google-chrome)](https://pranavkumaarofficial.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/pranavkumaarofficial)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:pranavkumaarofficial@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1f6feb,100:1f6feb&height=2&section=header" />

</div>

---

## 🔬 Research & Publications

<table>
<tr>
<td width="25%"><b>ICMLC 2026</b></td>
<td width="75%">
<b>When Graph Structure Hurts: Lightweight Path Ranking for Dense KG-RAG</b><br>
93.9% AUC · 13× fewer parameters than GNN baselines · Designed for dense, production-scale knowledge graphs
</td>
</tr>
</table>

---

## 🚀 Selected Systems & Public Projects

<table>
<tr>
<td width="30%"><b>Channel AI</b><br><sub>Conversational BI Platform</sub></td>
<td width="70%">

- Reduced enterprise reporting cycles **from days to minutes**
- **Deployed:** 4 enterprise pilots + 12 SMB environments  
- **Latency:** &lt;20s over multi-million-row analytical workloads  

<b>System Design</b>: Multi-agent LangGraph architecture over Apache Iceberg  
<b>Stack</b>: LangGraph · OpenAI Agents SDK · Iceberg · RAG · LlamaIndex · Qdrant · WhatsApp API  

🔗 https://github.com/pranavkumaarofficial/newdhatu-enterprise

</td>
</tr>

<tr>
<td><b>NLCLI Wizard</b><br><sub>Local LLM Tooling</sub></td>
<td>

- **83.3% accuracy** translating natural language → shell commands  
- Fully **offline CPU inference** (810 MB quantized model)  
- ~**1.5s latency**, zero external APIs  

<b>Technical</b>: Gemma 3 1B fine-tuned via QLoRA · GGUF Q4_K_M · llama.cpp  
<b>Data</b>: 1,500 manually verified command mappings  

🔗 https://github.com/pranavkumaarofficial/nlcli-wizard

</td>
</tr>
</table>

---

## 🧠 Production Case Studies (No Public Repository)

<table>
<tr>
<td width="30%"><b>OneSKU</b><br><sub>Hybrid Retrieval System</sub></td>
<td width="70%">

<sub>Implemented within a client-facing production environment; source code not publicly releasable.</sub>

- **94% precision** on catalog-matching benchmarks  
- &lt;15s query latency across multi-million SKU inventories  
- Rolled out across **20+ vendor catalogs**

<b>Key Design Insights</b>:
- Hybrid **BM25 + dense embeddings** outperform purely neural retrieval for noisy, heterogeneous catalogs  
- Explicit separation of categorical (exact-match) vs numerical (range-aware) attributes  
- Vendor-specific schema reconciliation logic

</td>
</tr>
</table>

---

## 🧪 Systems in Progress

<table>
<tr>
<td width="50%"><b>Efficient Agent Routing</b></td>
<td width="50%">Cost-aware agent selection for tool-heavy LLM workflows under strict latency budgets</td>
</tr>
<tr>
<td><b>Small Language Models for Analytics</b></td>
<td>Local inference, quantization, and structured reasoning for domain-specific business intelligence</td>
</tr>
</table>

---

## 🛠 Technical Focus Areas

<table>
<tr>
<td width="33%"><b>AI / ML Systems</b><br>
Multi-agent orchestration · RAG · PEFT · Quantization · Model optimization
</td>

<td width="33%"><b>Data & Infrastructure</b><br>
Apache Iceberg · PostgreSQL · Vector Databases · Docker · Kubernetes · Cloud platforms
</td>

<td width="33%"><b>Production Engineering</b><br>
FastAPI · Python · TypeScript · OAuth2 · PKI · HL7 / FHIR interoperability
</td>
</tr>
</table>

---

## 📊 GitHub Snapshot

<table>
<tr>
<td>
<img alt="GitHub Stats"
src="https://github-readme-stats.vercel.app/api?username=pranavkumaarofficial&show_icons=true&rank_icon=github&hide_border=true&cache_seconds=86400" />
</td>
<td>
<img alt="Top Languages"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=pranavkumaarofficial&layout=compact&hide_border=true&cache_seconds=86400" />
</td>
</tr>
</table>

---

<div align="center">

### 📫 Connect

[Portfolio](https://pranavkumaarofficial.github.io) ·
[LinkedIn](https://linkedin.com/in/pranavkumaarofficial) ·
[Email](mailto:pranavkumaarofficial@gmail.com)

<sub>Interests: multi-agent systems, local LLM deployment, scalable ML infrastructure</sub>

</div>
