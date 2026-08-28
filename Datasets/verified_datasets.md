# 📊 Curated Research Datasets

This document tracks verified, publicly accessible datasets and benchmark corpora specifically designed for Automated Claim Verification (ACV), scientific Natural Language Inference (NLI), citation integrity auditing, and quotation error detection in academic literature.

---

## 📋 Verified Dataset Registry
# 📊 Benchmark Datasets Registry

A curated collection of verified benchmark datasets used for Automated Claim Verification, Scientific Evidence Retrieval, and Citation Integrity Auditing.

---

## 1. SciFact
* **Source:** Allen Institute for AI (AI2)
* **Description:** 1.4K expert-annotated scientific claims paired with 5.1K abstracts from research papers. Includes sentence-level rationale annotations and veracity labels (*SUPPORTS*, *REFUTES*).
* **Application:** Fine-tuning NLI models for scientific evidence retrieval and detecting citation misinterpretation.
* **Link:** [SciFact Benchmark](https://github.com/allenai/scifact)

---

## 2. FEVER (Fact Extraction and VERification)
* **Source:** University of Sheffield / Cambridge
* **Description:** 185K claims derived from Wikipedia paired with evidence sentences for large-scale document extraction and factual integrity checks.
* **Application:** Training baseline document retrieval and stance classification pipelines.
* **Link:** [FEVER Dataset Official Site](https://fever.ai/)

---

## 3. PubMedQA
* **Source:** University of Pittsburgh / Carnegie Mellon University
* **Description:** 1K expert-annotated and 211K synthetic question-answering pairs derived from PubMed abstracts, evaluating factual agreement between text claims and source literature.
* **Application:** Auditing biomedical research claims and verifying citation context against PubMed abstracts.
* **Link:** [PubMedQA Official Site](https://pubmedqa.github.io/)

---

## 4. MultiFC (Multi-Domain Fact-Checking)
* **Source:** Copenhagen Natural Language Understanding (CopenLU)
* **Description:** A large-scale multi-domain dataset of 34K real-world claims annotated with evidence contexts and metadata across 26 fact-checking portals.
* **Application:** Cross-domain generalizability evaluation for automated claim verification.
* **Links:** [MultiFC ACL Paper Page](https://aclanthology.org/D19-1475/) | [CopenLU Official Project Page](https://copenlu.github.io/publication/2019_emnlp_augenstein/)
