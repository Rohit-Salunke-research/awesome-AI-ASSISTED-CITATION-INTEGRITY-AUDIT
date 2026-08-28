
# 💻 Open-Source Code Repositories for Automated Claim Verification

This document catalogs open-source codebases, model implementations, and benchmark baselines dedicated to automated claim verification, evidence retrieval, and scientific fact-checking.

---

## 📂 Repository Index

| Repository Name | Authors / Institution | Focus Area | Key Contributions | Link |
| :--- | :--- | :--- | :--- | :--- |
| **SciFact Base Repository** | Wadden et al. (AI2 / Univ. of Washington) | Scientific Fact-Checking | Official codebase for training baseline evidence retrieval and rationale classification models on scientific abstracts. | [allenai/scifact](https://github.com/allenai/scifact) |
| **MultiVerS** | Wadden et al. (AI2) | Multi-Task Fact Verification | Implements a unified task-conditioned model that handles rationale selection and claim prediction simultaneously across multiple domains. | [allenai/multivers](https://github.com/allenai/multivers) |
| **FEVER Baseline & API** | Thorne et al. (Univ. of Sheffield / Cambridge) | General Claim Verification | The foundational repository providing pipeline implementations for Wikipedia entity linking, document retrieval, and NLI verification. | [sheffieldnlp/fever-baselines](https://github.com/sheffieldnlp/fever-baselines) |
| **PubMedQA Evaluation Kit** | Jin et al. (Univ. of Pittsburgh / CMU) | Biomedical QA & Verification | Contains codebase, evaluation scripts, and model fine-tuning scripts for answer verification over biomedical literature. | [pubmedqa/pubmedqa](https://github.com/pubmedqa/pubmedqa) |
| **DeBERTa NLI Pipeline** | Microsoft Research | Natural Language Inference | Implementation of DeBERTa architectures optimized for textual entailment and stance detection tasks in evidence verification. | [microsoft/DeBERTa](https://github.com/microsoft/DeBERTa) |

---

## 🛠️ Usage Guidelines

* **Reproducibility:** All repositories included feature instructions for environment setup (`requirements.txt` / `environment.yml`) and evaluation metrics calculation.
* **Benchmarking:** Repositories serve as official baseline implementations for standardized datasets (SciFact, FEVER, PubMedQA).
