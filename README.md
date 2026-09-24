# Pranav Kumaar

Software engineer. I build developer tooling with a bias toward local execution: things that run on your machine, work offline, and tell you when they are not sure.

MS Computer Science at UMass Amherst. Previously two years building software for medical devices. Amherst, MA.

[Portfolio](https://pranavkumaarofficial.github.io) · [LinkedIn](https://linkedin.com/in/pranavkumaarofficial) · [Email](mailto:pranavkumaarofficial@gmail.com)

---

### Tools

**[venvy](https://github.com/pranavkumaarofficial/venvy)** · [PyPI](https://pypi.org/project/venvy/)
Audits every Python virtual environment on a machine for known-vulnerable and known-malicious packages, offline. Inventory reads `*.dist-info` as text and never imports the package it is scanning. Fails closed: a missing, corrupt, or empty advisory database refuses to scan rather than reporting a false all-clear. Semantic exit codes for CI. 229 tests on Windows, macOS, and Linux across Python 3.8 to 3.13. Every claim in the README has a command behind it in [docs/VERIFY.md](https://github.com/pranavkumaarofficial/venvy/blob/main/docs/VERIFY.md).

**[nlcli-wizard](https://github.com/pranavkumaarofficial/nlcli-wizard)**
Natural language to Docker commands using a fine-tuned Gemma quantized to GGUF, running on CPU with no network. I published 94% accuracy, discovered it had been measured on training data, and retracted it. The corrected figure is 46.6% on 116 handwritten tests, with a contamination-checking eval harness so anyone can reproduce both the number and the mistake. The per-category breakdown shows where a small model actually fails.

**[oauth-for-dummies](https://github.com/pranavkumaarofficial/oauth-for-dummies)** · [PyPI](https://pypi.org/project/oauth-for-dummies/)
Scaffolds working OAuth into a FastAPI project in one command, for six providers, with a debugger that shows the redirect and token exchange step by step. You own the generated code and there is no runtime dependency on the tool.

**[ping-claude](https://github.com/pranavkumaarofficial/ping-claude)**
Relays Claude Code permission prompts to a phone over Tailscale, so you can approve or deny from anywhere without a cloud service in the path. Runs entirely on your own machines.

**[python-est](https://github.com/pranavkumaarofficial/python-est)**
EST (RFC 7030) certificate enrollment server in Python.

---

### Open source

Two pull requests open against [PyJWT](https://github.com/jpadilla/pyjwt): [#1183](https://github.com/jpadilla/pyjwt/pull/1183) adds the received audience value to `InvalidAudienceError`, and [#1184](https://github.com/jpadilla/pyjwt/pull/1184) adds `to_dict()` and `to_json()` to `PyJWK` and `PyJWKSet`.

---

### Research

**When Graph Structure Hurts: Lightweight Path Ranking for Dense KG-RAG**, accepted at ICMLC 2026.
An MLP path scorer reaches 93.9% AUC on dense knowledge graphs, ahead of GCN and GAT baselines with roughly 13x fewer parameters. Code goes public after the conference.

---

### Systems

**[Channel AI](https://github.com/pranavkumaarofficial/channel-ai-enterprise)**
Conversational analytics over WhatsApp for non-technical users, across 12 pilot deployments. Five-stage pipeline where SQL generation is the last step, after a dialog agent resolves what the question actually means. Shut down as a venture. The repository is the architecture write-up, including the two failure classes that dominated production errors: temporal grain mismatch and categorical value linking. No code, and it says so.

---

### Working on

- Making nlcli-wizard installable in one paste on a machine without a compiler
- venvy: progress output on full-disk discovery, and closing the gap between the malicious-package feeds and known historical typosquats

---

`Python` `PyTorch` `FastAPI` `SQLite` `llama.cpp` `LangGraph` `Apache Iceberg` `Docker` `PostgreSQL` `TypeScript`
