<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ldtd-agh/.github/raw/main/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/ldtd-agh/.github/raw/main/banner-light.png">
    <img height="150" alt="LDTD-AGH" src="https://github.com/ldtd-agh/.github/raw/main/banner-dark.png">
  </picture>
</p>

<p align="center">
  <b>Language-Driven Therapy Design for Personalized Cancer Treatment</b><br>
  Combining fast AI simulation surrogates, physics-informed neural networks, and large language models<br>
  to give oncologists natural language control over tumor evolution modeling — currently focused on head and neck cancer.
</p>

<p align="center">
  <a href="https://www.ncn.gov.pl/en"><img src="https://img.shields.io/badge/Funded%20by-NCN%20OPUS--29-blue?style=flat-square" alt="NCN OPUS-29"/></a>
  <a href="https://www.agh.edu.pl/en"><img src="https://img.shields.io/badge/Institution-AGH%20University%20of%20Kraków-green?style=flat-square" alt="AGH University"/></a>
  <img src="https://img.shields.io/badge/Duration-2026–2029-orange?style=flat-square" alt="Duration"/>
  <img src="https://img.shields.io/badge/Focus-Head%20%26%20Neck%20Cancer-red?style=flat-square" alt="HNC"/>
</p>

---

## About

**LDTD-AGH** is the research GitHub organization for the NCN OPUS-29 project:

> *"Simulation of complex biological systems assisted by artificial intelligence: language-controlled model for cancer therapy planning"*

Led by **Prof. Witold Dzwinel** at AGH University of Science and Technology in Kraków, this 3-year project (2026–2029) develops a next-generation computational framework that bridges mechanistic tumor modeling, physics-informed machine learning, and clinical AI — enabling oncologists to plan and optimize cancer therapies through natural language.

---

## Research pillars

### 🧬 Fast simulation surrogates
Zero-dimensional ODE-based surrogate models (including the Ribba model) and 3D mechanistic tumor models for melanoma, glioblastoma, and HNSCC. We employ knowledge distillation from complex 3D teachers to lightweight student models, and a supermodeling framework that synchronizes multiple sub-models via data assimilation.

### ⚛️ Physics-informed and data-driven ML
Encoder–processor–decoder architectures for predicting tumor evolution from CT/PET/MRI sequences. Physics-Informed Neural Networks (PINNs) for spatio-temporal cancer dynamics (reaction-diffusion PDEs, logistic growth, therapeutic modulation) and hybrid supermodeling + PIML ensembles.

### 🔍 RAG/LLM integration
Retrieval-Augmented Generation systems with domain-specific oncology and pharmacotherapy knowledge bases, custom embedding models for cancer simulation outputs, vector database retrieval pipelines, and fine-tuned LLMs for clinical query answering (Self-RAG, CRAG, GraphRAG).

### 💬 Language-Driven Therapy Design (LDTD)
The unified LDTD framework — the project's flagship deliverable — allows oncologists to control simulations, generate hypotheses, and plan personalized therapies through natural language commands. It integrates all three pillars into a clinically validated, interactive system.

---

## Repository structure

| Repository | Description | Year |
|---|---|---|
TODO

---

## Deliverables

**End of Year 1 — Validated 0D Surrogate Model Framework**
A comprehensive suite of validated zero-dimensional surrogate models for tumor dynamics prediction under therapeutic and uncertain conditions.

**End of Year 2 — Hybrid AI-Physics Prediction Engine**
A validated hybrid supermodeling framework combining physics-informed neural networks with encoder-processor-decoder architectures and multi-model ensemble approaches.

**End of Year 3 — Complete LDTD Framework**
A fully functional, clinically validated Language-Driven Therapy Design framework enabling oncologists to interactively explore, plan, and optimize cancer treatment strategies through natural language.

---

## Clinical focus

**Head and neck squamous cell carcinoma (HNSCC / HNC)**

Data sources: TCIA (licensed), TCGA, SEER, and anonymized clinical data from collaborating Polish oncology institutions:
- Maria Skłodowska-Curie National Research Institute of Oncology, Gliwice
- Radiotherapy and Chemotherapy Clinic, 5 Military Clinical Hospital, Kraków
- Department of Otolaryngology and Head and Neck Oncological Surgery

---

## Team

| Name | Role | Expertise |
|---|---|---|
| **Prof. Witold Dzwinel** | Principal Investigator | Complex systems simulation, supermodeling, ML for biology |
| **Dr Bartosz Minch** | Co-Investigator | LLMs, RAG systems, MCP, domain-specific fine-tuning |
| **MSc Filip Reka** | PhD Student | Data science, multimodal LLMs, clinical AI |
| **Dr Leszek Siwik** | Co-Investigator | Agent-based modeling, nature-inspired optimization, PDE solvers |
| **Prof. Maciej Paszyński** | Co-Investigator | Complex systems simulation, supermodeling, ML for biology |

---

## Funding

This project is funded by the **National Science Centre of Poland (NCN)** under the OPUS-29 call, grant ID **648778**.

<p align="center">
  <sub>AGH University of Kraków · al. Mickiewicza 30, 30-059 Kraków, Poland</sub>
</p>
