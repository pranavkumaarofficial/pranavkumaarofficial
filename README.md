# Pranav Kumaar

Developer tooling with a bias toward local execution. Runs on your machine, works offline, tells you when it is not sure.

MS Computer Science, UMass Amherst. Two years shipping software for medical devices before that.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://pranavkumaarofficial.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranavkumaarofficial)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pranavkumaarofficial@gmail.com)
[![Location](https://img.shields.io/badge/Amherst,_MA-4A5568?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![llama.cpp](https://img.shields.io/badge/llama.cpp-1C1C1C?style=flat-square&logo=meta&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-1B7EC4?style=flat-square&logo=apache&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### Tools

**[venvy](https://github.com/pranavkumaarofficial/venvy)**
[![PyPI](https://img.shields.io/pypi/v/venvy?style=flat-square&color=3775A9&logo=pypi&logoColor=white)](https://pypi.org/project/venvy/)
[![Tests](https://github.com/pranavkumaarofficial/venvy/actions/workflows/tests.yml/badge.svg)](https://github.com/pranavkumaarofficial/venvy/actions/workflows/tests.yml)
[![Stars](https://img.shields.io/github/stars/pranavkumaarofficial/venvy?style=flat-square&color=555)](https://github.com/pranavkumaarofficial/venvy/)
Offline supply-chain audit of every Python environment on a machine. Reads package metadata as text, never imports what it scans, and refuses to report "clean" when its database is unusable. Every README claim has a command behind it in [docs/VERIFY.md](https://github.com/pranavkumaarofficial/venvy/blob/main/docs/VERIFY.md).

**[nlcli-wizard](https://github.com/pranavkumaarofficial/nlcli-wizard)**
[![Stars](https://img.shields.io/github/stars/pranavkumaarofficial/nlcli-wizard?style=flat-square&color=555)](https://github.com/pranavkumaarofficial/nlcli-wizard/)
Natural language to Docker commands. Fine-tuned Gemma, quantized to GGUF, CPU only, no network. I published 94% accuracy, found it was measured on training data, retracted it, and built the contamination-checking harness that produces the real number: 46.6%.

**[oauth-for-dummies](https://github.com/pranavkumaarofficial/oauth-for-dummies)**
[![PyPI](https://img.shields.io/pypi/v/oauth-for-dummies?style=flat-square&color=3775A9&logo=pypi&logoColor=white)](https://pypi.org/project/oauth-for-dummies/)
[![Stars](https://img.shields.io/github/stars/pranavkumaarofficial/oauth-for-dummies?style=flat-square&color=555)](https://github.com/pranavkumaarofficial/oauth-for-dummies/)
OAuth login into a FastAPI project in one command, six providers, with a step-by-step debugger for the redirect and token exchange.

**[ping-claude](https://github.com/pranavkumaarofficial/ping-claude)**
[![Stars](https://img.shields.io/github/stars/pranavkumaarofficial/ping-claude?style=flat-square&color=555)](https://github.com/pranavkumaarofficial/ping-claude/)
Claude Code permission prompts on your phone over Tailscale. No cloud service in the path.

**[python-est](https://github.com/pranavkumaarofficial/python-est)**
EST (RFC 7030) certificate enrollment server in Python.

---

### Open source

[![PyJWT #1183](https://img.shields.io/badge/PyJWT-%231183-000000?style=flat-square&logo=github)](https://github.com/jpadilla/pyjwt/pull/1183)
[![PyJWT #1184](https://img.shields.io/badge/PyJWT-%231184-000000?style=flat-square&logo=github)](https://github.com/jpadilla/pyjwt/pull/1184)

Open against [PyJWT](https://github.com/jpadilla/pyjwt): the received audience value in `InvalidAudienceError`, and `to_dict()` / `to_json()` on `PyJWK` and `PyJWKSet`.

---

### Research

**When Graph Structure Hurts: Lightweight Path Ranking for Dense KG-RAG**, accepted at ICMLC 2026.
An MLP path scorer reaches 93.9% AUC on dense knowledge graphs, ahead of GCN and GAT baselines with roughly 13x fewer parameters. Code public after the conference.

---

### Systems

**[Channel AI](https://github.com/pranavkumaarofficial/channel-ai-enterprise)**
Conversational analytics over WhatsApp, 12 pilot deployments. SQL generation is the last stage, after a dialog agent resolves what the question means. Shut down as a venture; the repo is the architecture write-up and says plainly that there is no code.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=pranavkumaarofficial&hide_border=true&theme=github-dark-blue&date_format=j%20M%5B%20Y%5D">
  <img height="170" src="https://streak-stats.demolab.com/?user=pranavkumaarofficial&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="Commit streak and total contributions">
</picture>
