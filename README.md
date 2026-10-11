# Hi, I'm Bharathi

I'm an MS Computer Science and Software Engineering student at the University of Washington Bothell. I'm doing my thesis research on high-performance GPU systems at the [Distributed Systems Laboratory](https://depts.washington.edu/dslab/) at UW Bothell.

I like building from first principles, especially when there's no playbook.

[![Portfolio](https://img.shields.io/badge/Portfolio-2ea44f?style=flat)](https://bharathiganeshkumar.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat)](https://www.linkedin.com/in/bharathi-ganesh-kumar/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-8250df?style=flat)](https://scholar.google.com/citations?user=vyNpfrIAAAAJ&hl=en)
[![Resume](https://img.shields.io/badge/Resume-d73a49?style=flat)](https://drive.google.com/file/d/1cGn2hmLDZWJzhBNSNYcSKtN6_QHDLiJr/view?usp=sharing)
[![Email](https://img.shields.io/badge/Email-e36209?style=flat)](mailto:bharathiganeshkumar07@gmail.com)

<a href="https://bharathiganeshkumar.github.io/"><img src="portfolio-preview.png" alt="Preview of my portfolio website" width="600"></a>

<sub>Click the image to visit my portfolio.</sub>

## Currently

**Graduate Research Assistant, [Distributed Systems Laboratory](https://depts.washington.edu/dslab/)** | Jun 2026 – Present
Advised by [Prof. Munehiro Fukuda](https://www.uwb.edu/faculty/munehiro-fukuda/)

- Researching thesis on [MASS CUDA](https://depts.washington.edu/dslab/MASS/), a **multi-GPU agent-based modeling framework** built in **C++/CUDA**, focused on **multi-GPU communication strategies (UVA, NCCL)**, **agent collision-handling optimization**, and **per-step execution performance**
- Re-engineered MASS CUDA's **Clang-based source-to-source translator** codegen on Rocky Linux to build against **CUDA 13.2 and LLVM 21**, writing **3 benchmarks (Heat2D, GameOfLife, SugarScape)** and validating them against the new translator

**Engagement Coordinator, WiCyS (Women in Cybersecurity), UW Bothell** | Sep 2026 – Present

I run the visual side of WiCyS at UW Bothell, from recruitment posters to social media graphics. I wanted cybersecurity to feel less intimidating and more welcoming, and design turned out to be a fun way to do it. I get to experiment, give our posters some personality, and hopefully make someone curious enough to stop by and say hi.

## Selected Work

### [GPU-Cost-Aware Bin-Packing Scheduler](https://github.com/BharathiGaneshkumar/gpu-cost-aware-bin-packing-scheduler) <sub>Jul 2026</sub>

A Kubernetes admission webhook that enforces GPU cost tiers and SLA eligibility at admission time, something native Kubernetes scheduling has no way to do.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![client-go](https://img.shields.io/badge/client--go-326CE5?style=flat) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![kind](https://img.shields.io/badge/kind-326CE5?style=flat) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

### [Quantum vs Classical ML on CAR T-Cell Data](https://github.com/BharathiGaneshkumar/quantum-pqk-car-t-hackathon) <sub>May 2026</sub>

Won at the UW x IBM Quantum Machine Learning Hackathon. A projected quantum kernel beat a classical SVM at predicting CAR T-cell cytotoxicity on the held-out test set.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat) ![Qiskit Runtime](https://img.shields.io/badge/Qiskit_Runtime-6929C4?style=flat) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![Projected Quantum Kernel](https://img.shields.io/badge/Projected_Quantum_Kernel-555555?style=flat) ![IBM Quantum (QPU)](https://img.shields.io/badge/IBM_Quantum_%28QPU%29-054ADA?style=flat)

### [Agentic Smart Building Maintenance System](https://github.com/BharathiGaneshkumar/agentic-bms) <sub>Oct 2026</sub>

A multi-agent system for predictive maintenance and complaint-driven fault resolution in sustainable smart buildings, built on real air handling unit data with explainable fault detection and energy-waste estimates. In progress.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat) ![SHAP](https://img.shields.io/badge/SHAP-555555?style=flat) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat) ![Jira MCP](https://img.shields.io/badge/Jira_MCP-0052CC?style=flat&logo=jira&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

### [Fault-Tolerant AI Inference Coordinator](https://github.com/BharathiGaneshkumar/fault-tolerant-ai-inference-coordinator) <sub>Aug 2025</sub>

A Raft consensus layer built from scratch in Go, eliminating single points of failure in AI inference request routing.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Raft (custom implementation)](https://img.shields.io/badge/Raft_%28custom_implementation%29-555555?style=flat) ![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat) ![Protocol Buffers](https://img.shields.io/badge/Protocol_Buffers-555555?style=flat) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat) ![Kubernetes (StatefulSets)](https://img.shields.io/badge/Kubernetes_%28StatefulSets%29-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

### [N-Body Gravitational Simulation](https://github.com/BharathiGaneshkumar/nbodyGravitationalSimulation) <sub>Feb 2026</sub>

A GPU-accelerated N-body gravitational simulator comparing sequential, OpenMP, and CUDA implementations, reaching over 100x speedup on a laptop GPU.

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white) ![OpenMP](https://img.shields.io/badge/OpenMP-555555?style=flat) ![Nsight Compute](https://img.shields.io/badge/Nsight_Compute-76B900?style=flat) ![Python (matplotlib)](https://img.shields.io/badge/Python_%28matplotlib%29-11557C?style=flat&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

### [DawgDen](https://github.com/BharathiGaneshkumar/DawgDen) (<a href="https://dawg-den.vercel.app/">live</a>) <sub>Sep 2025</sub>

A student housing platform that reads a lease for red flags before you sign it and makes a landlord's reputation impossible to quietly erase.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=flat&logo=auth0&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![Neon PostgreSQL](https://img.shields.io/badge/Neon_PostgreSQL-00A67E?style=flat&logo=postgresql&logoColor=white) ![Gemini API (Gemma 4)](https://img.shields.io/badge/Gemini_API_%28Gemma_4%29-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat)

### [Trope Chemistry](https://github.com/BharathiGaneshkumar/trope-chemistry) <sub>Jun 2026</sub>

A graph neural network for fanfiction engagement prediction, benchmarked in an ablation study against 6 other models to test whether trope structure actually beats plain text.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![PyTorch Geometric](https://img.shields.io/badge/PyTorch_Geometric-EE4C2C?style=flat) ![GraphSAGE](https://img.shields.io/badge/GraphSAGE-555555?style=flat) ![GAT](https://img.shields.io/badge/GAT-555555?style=flat) ![GIN](https://img.shields.io/badge/GIN-555555?style=flat) ![BERT+GAT](https://img.shields.io/badge/BERT%2BGAT-555555?style=flat) ![Sentence-BERT](https://img.shields.io/badge/Sentence--BERT-555555?style=flat) ![NetworkX](https://img.shields.io/badge/NetworkX-555555?style=flat) ![python-louvain](https://img.shields.io/badge/python--louvain-3776AB?style=flat) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)

### [Causal AI: Student Success](https://github.com/BharathiGaneshkumar/studentPerformanceCausalAI) <sub>Sep 2025</sub>

A causal discovery project separating what actually drives student grades from what only correlates with them, quantified with real treatment effects.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![causal-learn (PC, GES, NOTEARS)](https://img.shields.io/badge/causal--learn_%28PC%2C_GES%2C_NOTEARS%29-555555?style=flat) ![DoWhy](https://img.shields.io/badge/DoWhy-555555?style=flat) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![Graphviz](https://img.shields.io/badge/Graphviz-555555?style=flat) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)

### [FloodGuard AI](https://github.com/swetha7502/flood-resilience-qwen) <sub>Jul 2026</sub>

A simulated edge sensor network for flood early warning across 3 zones, staying operational through a 4-state graceful degradation ladder when the cloud drops.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=flat) ![Qwen (DashScope API)](https://img.shields.io/badge/Qwen_%28DashScope_API%29-615CED?style=flat) ![MCP (custom audit server)](https://img.shields.io/badge/MCP_%28custom_audit_server%29-555555?style=flat) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat)

### [OOO Negotiation Agent](https://github.com/swetha7502/ooo-agent) <sub>Jun 2026</sub>

A Slack bot where two independent agents negotiate task handoffs when someone goes out of office, instead of one bot reassigning work top-down.

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white) ![Slack Bolt](https://img.shields.io/badge/Slack_Bolt-4A154B?style=flat&logo=slack&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat) ![Slack Real-Time Search API](https://img.shields.io/badge/Slack_Real--Time_Search_API-4A154B?style=flat&logo=slack&logoColor=white)

### [ConflictMind](https://github.com/nitin-s17/conflictmind) <sub>Jun 2026</sub>

An AI agent with persistent memory that debates its own contradictory memories about you before resolving them, instead of silently overwriting one with the other.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) ![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat) ![Gemini 2.5 Flash](https://img.shields.io/badge/Gemini_2.5_Flash-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat) ![MongoDB Atlas (vector search)](https://img.shields.io/badge/MongoDB_Atlas_%28vector_search%29-47A248?style=flat&logo=mongodb&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-555555?style=flat) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Google Cloud Run](https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=flat&logo=googlecloud&logoColor=white)

## Research

- [From Attacks to Insights: XAI and Defense in Network Security](https://ieeexplore.ieee.org/document/10864205), IEEE ICSCNA 2024
- [OCULANG: Empowering Communication through Blink Language Detection](https://doi.org/10.36548/jsws.2024.4.003), IRO Journal on Sustainable Wireless Systems, 2024

## Experience

**IT Accessibility Assistant** | University of Washington Bothell | Jan 2026 – Jun 2026

- Remediated roughly **30 courses** to **WCAG 2.1 AA and ADA** standards across PDF, Word, and PowerPoint: alt text, heading hierarchy, color contrast, reading order, and table tagging. Ran **OCR** on scanned and handwritten sources first.
- **QA'd Claude-generated remediation outputs** against source documents, flagging errors and feeding structured findings back into the pipeline.
- On my own initiative, built a **web app** that logs accessibility issues by type and filter and converts them into Claude-friendly markdown, which consistently improved remediation accuracy by **30%**.

**Associate Applications Developer** | [Oracle](https://www.oracle.com/in/) | Jul 2024 – Aug 2025

[Oracle Utilities Application Framework (OUAF)](https://docs.oracle.com/en/industries/utilities/framework/264/sdk-dev-guide/index.html), Product Development and Cloud Operations

- Owned migration of an enterprise **cloud release platform serving 100+ customers** across APAC and EMEA to **independent infrastructure** end-to-end on Linux, navigating ambiguous requirements to architect **standalone SQL-based databases**, **PL/SQL application layers**, **REST APIs** and engineer **data pipeline fixes for cross-database sync failures** with no prior precedent to work from.
- Built **CI/CD and version-control pipeline from scratch** using **Liquibase changelogs** and CLI-based scripting and developer tooling, automating **Git-based promotion across 3 environments** and replacing manual, error-prone deployments with a standard workflow.
- Configured **SSO (SAML, OAuth 2.0, OIDC)** and **DB-level access control (ACL/ACE)**, coordinating with DBA and platform teams to manage security and permissions across **6+ stakeholder groups**.
- Delivered **high availability via Oracle Data Guard disaster recovery** across 3 environments, collaborating with infrastructure and DBA teams to validate setup and running **failover tests** to verify recovery behavior under failure.
- Designed and delivered **runbooks and troubleshooting guides**, along with an **18-session video training series** demonstrating strong communication skills while mentoring new team members on platform architecture and operations, adopted as the team's standard onboarding process.
- Resolved production issues across Classic and Redwood interfaces, including **60+ UI defects** through multiple rounds of code review, one of which was a **hierarchical permission bug** that required **overhauling the entire menu structure** across multiple product versions.
- Coordinated **6 master controller release cycles** on production systems hosted on **OCI** and built a **cloud cost optimization and monitoring dashboard tracking 100+ environments**, identifying idle environments and reducing unnecessary infrastructure spend.

**Applications Development Intern** | [Oracle](https://www.oracle.com/in/) | Jan 2024 – Jul 2024

- Migrated a legacy internal knowledge base to a **MoinMoin wiki** behind an **Nginx reverse proxy**, added team-level access control, and automated **broken-link detection** in Python, fixing **500+ broken links**.
- Automated **14 regression workflows** using object-oriented **Selenium and Java** test design alongside the Oracle Utilities Testing Accelerator, across 3 product versions and 9 environment instances weekly, **reducing testing time by 30%** and saving an estimated **5-6 hours of manual testing per week**.
- Resolved **60+ front-end defects** across OUAF's Classic and Redwood interfaces in JavaScript and Java.

**Associate Developer Intern** | [SAP Labs India](https://www.sap.com/india/about/labs-india.html) | May 2023 – Jul 2023

Built an **emergency financial aid disbursement application** for **17,000+ SAP Labs India employees** across 5 locations, digitizing the full insurance disbursement flow end-to-end with **TypeScript** and **REST APIs** in **Node.js and Express.js**, using **Micro Frontend architecture and Turbo Repo** on **SAP BTP**.

## Education

**M.S. Computer Science and Software Engineering** | [University of Washington, Bothell](https://www.washington.edu/) | Sep 2025 – Jun 2027

GPA 4.00 / 4.00. Coursework: High-Performance Computing, Distributed Systems, Deep Learning, Machine Learning

**B.E. Computer Science and Engineering** | [PSG College of Technology](https://www.psgtech.edu/), Coimbatore, India | Oct 2020 – May 2024

GPA 9.28 / 10.0, First Class with Distinction. Coursework: Data Structures and Algorithms, Operating Systems, Computer Networks, DBMS, Object-Oriented Programming
