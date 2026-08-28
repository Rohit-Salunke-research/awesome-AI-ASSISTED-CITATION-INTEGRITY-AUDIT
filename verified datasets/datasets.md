# 📊 Curated Research Datasets

This document tracks verified, publicly accessible datasets and benchmark corpora specifically designed for Automated Claim Verification (ACV), scientific Natural Language Inference (NLI), citation integrity auditing, and quotation error detection in academic literature.

---

## 📋 Verified Dataset Registry

| Dataset Name | Source / Provider | Description | Primary Application | Link / Repository |
| :--- | :--- | :--- | :--- | :--- |
| **SciFact** | Allen Institute for AI (AI2) | Expert-annotated dataset of 1,409 scientific claims paired with evidence sentences extracted from 5,183 PubMed research abstracts. | Benchmark for scientific claim verification, abstract evidence retrieval, and entailment (SUPPORT / CONTRADICT / NEI). | [SciFact Dataset](https://scifact.allenai.org/) |
| **FEVER (Fact Extraction and VERification)** | University of Cambridge | Large-scale open-domain dataset containing 185,445 claims generated from Wikipedia paired with evidence passages. | Foundational benchmark for pipeline training in information retrieval and claim-evidence NLI engines. | [FEVER Project](https://fever.ai/) |
| **Biomedical Citation Integrity Corpus (Sarol et al., 2024)** | University of Illinois Urbana-Champaign | Human-annotated corpus of biomedical full-text publications evaluating in-text citation accuracy and quotation errors. | Training and evaluating NLP models specifically on misinterpreted genuine citations and quotation distortions. | [PubMed Central Corpus](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11231046/) |
| **PubMedQA** | NIH / National Library of Medicine | Biomedical question-answering dataset collected from PubMed abstracts where answers are validated against full-text conclusions. | Evaluating domain-specific semantic entailment, complex medical reasoning, and evidence extraction. | [PubMedQA Project](https://pubmedqa.github.io/) |

---

## 🎯 Dataset Selection & Evaluation Criteria

All datasets included in this repository have been audited against the following scholarly standards:

1. **Domain Relevance:** Specifically targeted at biomedical, technical, or open-domain claim verification and natural language inference.
2. **Annotation Rigor:** Annotated by domain experts (e.g., medical professionals, NLP researchers) rather than crowdsourced without validation.
3. **Reproducibility:** Publicly available with open access licenses, well-documented schemas, and standard train/val/test splits.
4. **Citation Context Support:** Provides fine-grained sentence-level or paragraph-level annotations to support cross-document claim alignment.
