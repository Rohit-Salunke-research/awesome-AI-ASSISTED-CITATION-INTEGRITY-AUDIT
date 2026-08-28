
# 🛠️ Verified NLP & Automated Claim Verification (ACV) Tools

This document cataloging key software libraries, frameworks, and NLP toolkits utilized for automated claim verification, citation context extraction, full-text semantic parsing, and natural language inference (NLI).

---

## 📋 Software & Toolkit Registry

| Tool Name | Developer / Organization | Primary Function | Key Features | Project / Repository Link |
| :--- | :--- | :--- | :--- | :--- |
| **Hugging Face Transformers** | Hugging Face | Pre-trained Transformer Models | Provides accessible APIs and fine-tuning pipelines for state-of-the-art architectures (BERT, RoBERTa, DeBERTa, T5) used in claim verification and NLI engines. | [Hugging Face Hub](https://huggingface.co/docs/transformers/index) |
| **AllenNLP** | Allen Institute for AI (AI2) | Deep Learning NLP Framework | PyTorch-based NLP library specifically engineered for scientific text processing, fine-grained evidence extraction, and complex textual entailment models. | [AllenNLP GitHub](https://github.com/allenai/allennlp) |
| **spaCy** | Explosion AI | Industrial-Strength NLP | High-performance tokenization, named entity recognition (NER), dependency parsing, and sentence boundary detection for extracting citation contexts. | [spaCy Official Site](https://spacy.io/) |
| **Sentence-Transformers (SBERT)** | UKP Lab (TU Darmstadt) | Semantic Text Embeddings | Computes dense vector representations of sentence pairs, enabling fast BM25 re-ranking and semantic similarity search across reference abstracts. | [SBERT Documentation](https://www.sbert.net/) |
| **Stanza** | Stanford NLP Group | Biomedical & Multilingual Pipeline | Official Stanford Python NLP package featuring specialized pre-trained models for biomedical literature processing (BioNLP) and clinical entity extraction. | [Stanford Stanza](https://stanfordnlp.github.io/stanza/) |

---

## 🎯 Selection & Evaluation Criteria

Tools included in this registry are selected based on the following technical standards:

1. **Academic Adoption:** Widely utilized in peer-reviewed scientific NLP research and benchmarks (e.g., SciFact, FEVER).
2. **Domain Adaptation:** Offers specialized pre-trained weights for scientific and biomedical corpora (PubMed, arXiv).
3. **Open-Source Availability:** Maintained with active open-source licenses, comprehensive documentation, and community support.
4. **Pipeline Integration:** Supports modular integration into end-to-end evidence retrieval and semantic classification workflows.
