# NLP Assignment 2025 – Semantic Reconstruction & Similarity Analysis

## 📚 Overview
This repository contains the implementation of three deliverables for the NLP course assignment 2025. The focus is on transforming ambiguous or grammatically incorrect texts into semantically accurate and well-structured versions, analyzing their meaning through embeddings, and visualizing their semantic shifts.

---

## 📦 Deliverables

### ✅ Deliverable 1: Text Reconstruction
- Manual and automated reconstruction of two unstructured texts.
- NLP pipelines used: **spaCy**, **TextBlob**, **BART (HuggingFace)**.
- Cosine similarity analysis using **SentenceTransformers**.

### ✅ Deliverable 2: Computational Similarity Analysis
- Use of **GloVe** and **BERT** embeddings to analyze word-level and sentence-level similarity.
- Computation of cosine similarity between original and reconstructed text embeddings.
- Visualization using **PCA** and **t-SNE**.

### ✅ Deliverable 3: Structured Report
- Includes all methodology, analysis, results, discussion, and the Bonus (Masked Clause Input).
- Submitted separately in `.docx` / `.pdf` format.

---

## 📁 Repository Structure

```
.
├── paradoteo1_reconstruction.ipynb
├── paradoteo2_similarity_analysis.ipynb
├── .gitignore
├── .env
├── pyproject.toml
├── environment.yml
└── README.md
```

---

## 🧪 Installation & Execution

### Poetry (Recommended)

```bash
pip install poetry
poetry install
poetry shell
```

### Conda

```bash
conda env create -f environment.yml
conda activate nlp-2025-env
```

---

## 🔐 Security

- API keys or tokens (if used) should be stored in `.env`
- `.gitignore` excludes secret or unnecessary files

---

## ✍️ Author

*Your Full Name*  
*Your University - NLP Course 2025*

---

## 🔗 Notes

- The report file for Deliverable 3 is not included here. Please refer to the `.docx` or `.pdf` file submitted via the designated platform.
- All code is fully reproducible with the given environment configurations.
