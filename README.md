# 🛡️ femi Oyesanya (@oyesanyf)
> **Security Professional · Detection Engineer · AI Systems & AppSec Architect**

[![EDR Testing](https://img.shields.io/badge/EDR%20Testing-MITRE%20ATT%26CK%20v19.2-critical?style=for-the-badge&logo=shield&logoColor=white)](https://github.com/oyesanyf/Edrtest)
[![Detection Engineering](https://img.shields.io/badge/Detection-Engineering%20%26%20Telemetry-blue?style=for-the-badge&logo=powershell&logoColor=white)](https://github.com/oyesanyf/Edrtest)
[![Core Stack](https://img.shields.io/badge/Stack-Python%20%7C%20PowerShell%20%7C%20Rust-success?style=for-the-badge&logo=python&logoColor=white)](https://github.com/oyesanyf)
[![Website](https://img.shields.io/badge/Portfolio-femi.oyesanya.io-orange?style=for-the-badge&logo=googlechrome&logoColor=white)](https://femi.oyesanya.io)

---

### ⚡ About Me
I specialize in building defensive validation tools, security automation pipelines, and AI-driven systems.
- 🎯 **Primary Focus:** Endpoint Detection and Response (EDR) validation, behavioral telemetry (Sysmon, ETW 4688), and MITRE ATT&CK matrix automation.
- 🔍 **Application Security:** Static code analysis (SAST), Abstract Syntax Tree (AST) inspection, and IDE security plugins.
- 🤖 **AI Systems:** Multi-model LLM orchestration, agentic reasoning workflows, and AI code verification.
- 🌐 **Personal Site:** [femi.oyesanya.io](https://femi.oyesanya.io)

---

### 🚀 Featured Security & Engineering Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| [**AgentOctopus**](https://github.com/oyesanyf/AgentOctopus) | Single-binary Rust deterministic AI agent containment runtime enforcing RT-ASP sanitizers, AWS Cedar v4.13 PARC policy, Wasmtime v49.0.4 capability sandboxing, native OS kernel sandboxes (Landlock/seccomp, AppContainer, Seatbelt), credential-masking proxy, and `<2ms` binary/SBOM shields. | `Rust`, `AWS Cedar`, `Wasmtime`, `Landlock / AppContainer`, `AgentMesh` |
| [**OshoosiClaw**](https://github.com/oyesanyf/OshoosiClaw) | Autonomous decentralized Endpoint Detection & Response (EDR) and AI agent containment platform combining pre-execution kernel blocking (Windows Ring-0 / Linux eBPF), 7-Ring Cedar containment, TPM 2.0 attestation, post-quantum P2P consensus, and binary reverse engineering. | `Rust`, `Python`, `eBPF / ETW`, `YARA`, `Cedar` |
| [**KillSwitch**](https://github.com/oyesanyf/killswitch) | Zero-dependency Agentic EDR & Runtime Governance Kill-Switch enforcing pre-actuation AI agent governance (Google CAGE / APC), sub-microsecond OpenTelemetry/OpenLineage DLP egress blocking, and OS kernel isolation (Windows WFP, macOS `/dev/pf`, Linux Netlink/Landlock). | `Rust`, `Windows WFP`, `Linux Landlock`, `OpenTelemetry` |
| [**RedactX**](https://github.com/oyesanyf/RedactX) | Calibrated, single-pass clinical PHI / PII detector and exact span localizer fine-tuned via LoRA on Google's VaultGemma-1B, achieving 99.28% HIPAA Safe Harbor recall on Harvard n2c2 2014 EHR notes without generative hallucination. | `Python`, `PyTorch`, `VaultGemma-1B`, `LoRA`, `FastAPI` |
| [**QuorumRAG**](https://github.com/oyesanyf/QuorumRAG) | Local-first peer-to-peer Retrieval-Augmented Generation (RAG) & RLM daemon with hybrid LanceDB + Tantivy BM25 search, 100% verbatim citation grounding, Ed25519 `libp2p` mesh scatter-gather, and three-engine HIPAA/PII airlock DLP. | `Rust`, `LanceDB`, `Tantivy`, `libp2p`, `Ollama` |
| [**RFCHunt**](https://github.com/oyesanyf/rfchunt) | Specification-driven autonomous protocol research swarm and differential buffer ruler orchestrated via LangGraph to extract normative grammar rules from IETF & PQC RFCs, synthesize boundary/desynchronization probes, and delta-debug reproducible anomalies. | `Python`, `LangGraph`, `HTTP/TLS`, `Ollama`, `PQC` |
| [**ArXiv-to-Code**](https://github.com/oyesanyf/arxiv-to-code) | Autonomous arXiv paper discovery, 3-class Google LangExtract character-span grounding, Paper-to-Python synthesis, DynaRot hardware-aware model routing, and ShinkaEvolve + OpenEvolve evolutionary search (CLI & 8-tool MCP Server). | `Python`, `LangExtract`, `MCP`, `Evolutionary AI`, `Ollama` |
| [**ModelFusion**](https://github.com/oyesanyf/ModelFusion) | Open-weight compound intelligence runtime uniting Master CLI, HugOS IDE (sub-8ms ReST-RL preemption), AI-native Chromium browser, and a 173-tool Universal MCP Server with 2M+ model routing, multi-model consensus, and ACDSO Pareto AutoML. | `Rust`, `Python`, `JavaScript`, `MCP`, `Chromium CDP` |
| [**Mechanistic Interpretability**](https://github.com/oyesanyf/Mechanistic_Interpretability) | Cross-lingual LLM safety alignment & mechanistic interpretability audit probing safety circuit fragility across African languages (Yoruba, Igbo, Hausa, Swahili) vs. English via layer activation patching and neuron-level causal interventions. | `Python`, `PyTorch`, `Transformers`, `Gemma-2` |

---

### 🌐 Open-Source Contributions & Security Advisories

| Repository | Contribution | Highlights |
| :--- | :--- | :--- |
| [**google/cybernetic-agent-governance-engine**](https://github.com/google/cybernetic-agent-governance-engine) | [**PR #743**](https://github.com/google/cybernetic-agent-governance-engine/pull/743) *(Merged)* | Designed fail-closed Layer 1 NIST SC-7 workload quarantine enforcement (`quarantine_guard.py`, `probe_workload_quarantine()`) with verified Linkerd mTLS identities, KMS-signed refusal receipts, and `503`/`413` guards; adopted across all 6 gateway surfaces in [**PR #848**](https://github.com/google/cybernetic-agent-governance-engine/pull/848). |
| [**google/cybernetic-agent-governance-engine**](https://github.com/google/cybernetic-agent-governance-engine) | [**GHSA-797p-rrgm-4p56**](https://github.com/google/cybernetic-agent-governance-engine/security/advisories/GHSA-797p-rrgm-4p56) + 3 Accepted Advisories | Credited in `SECURITY.md` for published High-severity advisory `GHSA-797p-rrgm-4p56` (CVSS 7.6, fixed in `#813`), plus 3 additional accepted & remediated vulnerability disclosures via GitHub Private Vulnerability Reporting (pending coordinated publication). |
| [**google/agentmesh**](https://github.com/google/agentmesh) | [**PR #887**](https://github.com/google/agentmesh/pull/887) *(Merged)* | Contributed a Wasmtime capability-based sandbox example and documentation demonstrating isolated agent execution on AgentMesh under dedicated per-sandbox cryptographic identity (closes `#886`). |

---

### 🛠️ Technical Arsenal

```yaml
Detection & SecOps:
  - MITRE ATT&CK Enterprise Matrix (v19.2)
  - EDR / XDR Telemetry Validation (Defender for Endpoint, CrowdStrike, SentinelOne)
  - Atomic Red Team Unit Testing (1,587+ Windows Tests)
  - Windows Security Audit Events (4688, 4624, 7045, 1102) & Sysmon
  - KQL Advanced Hunting & Detection Rule Authoring

Development & Automation:
  - Languages: Python 3.10+, PowerShell 5.1/7+, TypeScript, Rust, Java
  - Protocols & CTI: WinRM / WS-Management, STIX 2.0 / TAXII
  - Automation: Git, CI/CD, Containerization, Agentic AI Systems
```

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=oyesanyf&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="femi's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=oyesanyf&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages" />
</p>

---

<p align="center">
  <b>Let's Connect:</b> <a href="https://femi.oyesanya.io">Website</a> · <a href="https://github.com/oyesanyf">GitHub</a>
</p>
