# Anuroop Ashok Shivdasan

**ML Engineer · MLDevOps & GenAIOps · Multi-Cloud (Azure · AWS · GCP)**

MSc Data Science graduate (Feb 2026) and Associate ML Engineer with 1+ years of industry experience building and maintaining MLDevOps pipelines for automated pharmaceutical document review. I specialize in custom ML model deployment, GenAIOps pipeline engineering, CI/CD automation, RAG systems, multi-agent architectures, and production AI for enterprise solutions.

📧 shivandru@gmail.com · 📱 +49 176 22565483 · 💼 [LinkedIn](https://www.linkedin.com/in/anuroop-shivdasan-79b055166/) · 📍 Magdeburg, Germany

---

## 💼 Experience

**Associate Machine Learning Engineer** — Quantiphi Analytics Solutions Pvt. Ltd. · Mumbai, India · Aug 2022 – Oct 2023

- *Data Engineer (Definity Financial, Apr–Oct 2023)* — Migrated legacy Pentaho jobs to Airflow on GCP via Python DAGs; built and validated 17 DAGs for BigQuery warehouse integration.
- *Associate MLE (Cerevel Therapeutics, Nov 2022–Apr 2023)* — Built and maintained Cloud Functions running MLDevOps pipelines for automated medical-document review from an eTMF server; shipped 4 custom classification pipelines (Financial Disclosures 3K PDFs, PPD Reports 1.5K, Hypercare SOWs 2K, FDA 1572 1K); trained Vertex AI AutoML models with custom Document AI parsers.
- *MLE Intern (Unum Insurance, Aug–Nov 2022)* — Built AutoML pipeline tagging 1,000+ medical underwriting documents via Cloud Functions.

---

## 🎓 MSc Thesis — LatBOND

**Latency-Budgeted Onset and Note Detection (GCP)** (Nov 2025 – Feb 2026) — real-time music transcription closing the distribution-shift gap between offline training and memory-constrained deployment, extending Hu et al. (ISMIR 2025) with a matched-training methodology.

- Trained **42 models** (3 architectures × 5 latency budgets × 3 conditions) on Vertex AI, orchestrating parallel jobs across T4/L4/A100 GPUs with Docker and automated GCS result upload
- Solved a deployment distribution-shift problem (models trained on 3–10s sequences degrading under 370–670ms real-world memory constraints); matched training outperforms truncated inference across all 15 architecture-budget combinations (**+0.87 pp avg F1**)
- Discovered via controlled ablation that a stepped geometric curriculum (500→250→125→62→target frames) is essential — removing it drops performance by 2.67 pp

→ **[LatBOND-Framework](https://github.com/lAteralthInklAbs/LatBOND-Framework)** · Python · PyTorch · Vertex AI

---

## 🛠️ Portfolio Projects

Production-pattern implementations demonstrating enterprise MLOps, GenAIOps, and edge deployment.

### [safedoc-ai](https://github.com/lAteralthInklAbs/safedoc-ai) — GDPR-Compliant Document Intelligence (Azure)
Enterprise document search retrieving answers from technical manuals with zero PII exposure under GDPR.
- End-to-end GDPR-compliant RAG pipeline (ingestion → PII detection → hybrid retrieval → grounded generation)
- Custom German PII recognizers (IBAN checksum, Steuer-ID check digit) at 0.95+ recall; RAGAS eval (groundedness 0.80+, faithfulness 0.85+) as a CI promotion gate
- Bicep IaC (ML workspace, AI Search, Container Apps, Key Vault) + GitHub Actions with 75%+ coverage target

`Azure OpenAI · AI Search · Container Apps · Presidio · FastAPI · MLflow · Docker · Bicep`

### [logiagent](https://github.com/lAteralthInklAbs/logiagent) — Multi-Agent Supply Chain Decisions (Azure)
Autonomous agents detecting supply chain disruptions and proposing cost-optimised mitigations with a SAP-compatible data layer.
- LangGraph multi-agent system (conditional routing, parallel execution, cycle detection) with Cosmos DB checkpointing for full decision replay
- Bayesian risk scorer + OR-Tools LP optimizer (15% cost savings vs naive allocation), 4-tier progressive constraint relaxation, HITL escalation
- SAP S/4HANA-compatible mock (MM/SD, 50 suppliers, 200 materials, 500 POs) with Repository pattern for zero-code swap to live OData v4; Hypothesis property tests (200+ examples)

`Azure OpenAI · Cosmos DB · Event Grid · LangGraph · OR-Tools · Prophet · FastAPI · MLflow · Bicep`

### [edgedeploy](https://github.com/lAteralthInklAbs/edgedeploy) — ISO 26262 Automotive Edge MLOps (AWS)
End-to-end pipeline compressing pre-trained automotive models for edge hardware with ISO 26262 safety gates.
- QAT engine with per-layer sensitivity analysis and mixed-precision (INT8/FP16/FP32) — 4× compression at <1% accuracy loss; ONNX export with target-runtime validation
- 3-detector drift ensemble (PSI + MMD + ADWIN) with weighted voting and temporal persistence filter — auto-rollback under 60s
- BFS requirements-traceability graph enforcing 100% ISO 26262 coverage (deployment hard-blocked on gaps); canary rollout (5/50/100%) via Terraform

`SageMaker · Neo · Model Registry · Model Monitor · IoT Greengrass · ONNX · TensorRT · Terraform`

---

## 🔧 Technical Skills

**Cloud:** Azure (OpenAI, AI Search, Container Apps, Durable Functions, Event Grid, Cosmos DB, Microsoft Foundry) · AWS (SageMaker, Model Monitor, CodePipeline, IoT Greengrass) · GCP (Vertex AI, BigQuery, Document AI, Cloud Functions)
**AI/ML:** RAG (hybrid BM25+dense, RRF, RAGAS) · Multi-Agent (LangGraph) · LLMs (GPT-4o, prompt flow) · Vector DBs (AI Search, Qdrant) · PyTorch · TensorFlow · SpaCy · ONNX · AutoML · Bayesian Risk Scoring · OR-Tools LP
**MLOps / IaC:** MLflow · SageMaker Pipelines · Airflow · Model Registry · Drift Detection (PSI, MMD, ADWIN) · CI/CD (GitHub Actions, CodePipeline) · Docker · Bicep · Terraform
**Enterprise:** GDPR/Datenschutz (Art. 5/6/17/25/30/35, Presidio) · ISO 26262 · SAP S/4HANA (MM/SD, OData v4) · OWASP LLM Top 10 · Human-in-the-Loop
**Languages:** Python (PyTorch, FastAPI, Pydantic, asyncio, Hypothesis) · SQL · JavaScript · Bash

---

## 🎓 Education

**MSc Data Science** — University of Europe for Applied Sciences, Potsdam · Sept 2024 – Feb 2026

**BE Computer Engineering** — Lokmanya Tilak College of Engineering, Mumbai University · 2012 – 2018

---

## 📜 Certifications

- **Microsoft AI-300** — Operationalizing ML and GenAI Solutions (MLOps Engineer Associate) · *Pursuing*
- **Microsoft AI-103** — Azure AI App and Agent Developer Associate · *Pursuing*

---

## 🌐 Languages

English (C1, IELTS 7.0) · German (A2, B1 exam Jul–Aug 2026) · Malayalam (Native) · Hindi (Fluent) · Marathi (Fluent)
