# Software Engineering for Cyber-Physical Systems Lab

**University of the Pacific, School of Engineering and Computer Science, Stockton, California.**
Led by Dr. Solomon Berhe.

We study how software ecosystems change: how updates, vulnerabilities and community
reports move through the systems that depend on them, and how AI agents can monitor,
explain and triage that change without hallucinating. Our work combines software
engineering, cyber-physical systems and the Internet of Things.

**Lab site:** https://se4cps.github.io/lab/research · **Platform:** https://releasetrain.io

## Research areas

- Agentic software engineering: multi-agent retrieval-augmented pipelines for software-update questions
- Guardrails for AI agents: goals, deterministic checks and measurable compliance for agentic systems
- Modeling software ecosystems: versions, dependencies and security updates across products
- Secure software engineering and IoT security (NIST IR 8259A)
- Internet of Things: edge AI, sensing, software-defined networking
- Clinical and health informatics; ontology and model-driven engineering

## releasetrain

An open-source framework that tracks software updates, CVEs and community discussion
signals across ecosystems and exposes them through a public API, a live dashboard and
an agentic question-answering pipeline. It is both a research instrument and a running
service at [releasetrain.io](https://releasetrain.io).

| Repository | What it is |
|---|---|
| [releasetrain-client](https://github.com/SE4CPS/releasetrain-client) | The web client: feed, least-stable releases, Ask pipeline, admin views |
| [releasetrain-inventory](https://github.com/SE4CPS/releasetrain-inventory) | CLI that lists a machine's installed software and exports an SBOM (CycloneDX or SPDX); on [PyPI](https://pypi.org/project/releasetrain-inventory/) |
| [releasetrain-sentiment](https://github.com/SE4CPS/releasetrain-sentiment) | Author-vs-community sentiment divergence in software-update discussions; on [PyPI](https://pypi.org/project/releasetrain-sentiment/) |
| [releasetrain-triage-bench](https://github.com/SE4CPS/releasetrain-triage-bench) | Reproducible benchmark for guardrail compliance in agentic update triage |
| [releasetrain-pip-package](https://github.com/SE4CPS/releasetrain-pip-package) | Python package and CLI that analyzes a software stack and suggests fixes, with an agent mode |
| [Research-on-Software-Updates](https://github.com/SE4CPS/Research-on-Software-Updates) | Architecture, data flow and API reference of the platform |

## Selected publications

- An Adaptive Multi-Agent RAG Architecture for Software Ecosystem Update Monitoring. ACM CAIS Workshop on Agentic Software Engineering, 2026.
- A Hallucination-Resistant RAG System for Software Update Queries. Procedia Computer Science, vol. 280, pp. 913–920 (EDI40 2026).
- Real-Time Dynamic Routing in Software-Defined Networks with Reinforcement Learning for IoT Edge Networks. Procedia Computer Science, vol. 280, pp. 921–928.
- AniLarm: AI for Small Animal Detection Under Cars Using Thermal Camera. IEEE Conference on Artificial Intelligence (CAI), 2025, pp. 741–746.
- Securing IoT Edge Devices: Applying NIST IR 8259A to a Realtime Animal Detection System. NDSS Workshop on Security and Privacy in Standardized IoT (SDIoTSec), 2025.
- IoT Software Updates: User Perspectives in the Context of NIST IR 8259A. NDSS SDIoTSec, 2025.

The full list, with papers, slides, posters and data, is on the [lab site](https://se4cps.github.io/lab/research/).

## Teaching

Course repositories (starter code, labs, class projects) are named by year and course,
for example `2026-COMP-175` (System Administration and Security) and `2026-COMP-051`
(Introduction to Programming in C++). Slides for every course are on the
[lab site](https://se4cps.github.io/lab/).

## Working with us

Students at the University of the Pacific who want to work on releasetrain, IoT or
agentic software engineering: email sberhe@pacific.edu with the project you are
interested in and the courses you have taken. Issues and pull requests on any
repository are welcome.
