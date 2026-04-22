# 🚀 Explainability of Text Processing and Retrieval Methods

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Paper](https://img.shields.io/badge/Paper-ACM_CSUR-red.svg)](https://dl.acm.org/doi/pdf/10.1145/3801957)
[![arXiv](https://img.shields.io/badge/arXiv-2212.07126-b31b1b.svg)](https://arxiv.org/abs/2212.07126)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

</div>

## 🌟 About This Repo
This is the official repository for the survey paper: **[Explainability of Text Processing and Retrieval Methods: A Survey](https://dl.acm.org/doi/pdf/10.1145/3801957)**, accepted in **ACM Computing Surveys (CSUR)**. 

This repository curates a comprehensive, continuously updated list of papers, resources, and tools related to the explainability and interpretability of Information Retrieval (IR) and Natural Language Processing (NLP) methods. It covers approaches from explaining traditional statistical models to Neural Ranking Models (NRMs), and modern Retrieval-Augmented Generation (RAG) systems.

## ⚡️ News
- **[2026/02]** 🎉 Our survey paper has been accepted and published in *ACM Computing Surveys*!
- **[2026/04]** 🚀 We released this Awesome list to track the latest research in Explainable Text Processing and IR.

## 🌳 Contents
- [🌟 About This Repo](#-about-this-repo)
- [📖 Cite Our Work](#-cite-our-work)
- [📚 Overview of the Survey](#-overview-of-the-survey)
- [📑 Paper List](#-paper-list)
  - [1. Categorising Explanation Methods](#1-foundational-concepts--taxonomies)
  - [2. Basic Methods for Constructing Post-hoc Explanations](#2-basic-posthoc-methods)
    - [2.1 Using probing classifiers to construct global explanations](#21-probing-global-explanations)
    - [2.2 Model-agnostic, local explanations](#22-model-agnostic-local-explanations)
  - [3. Evaluating explanations](#3-evaluate-explanations)
  - [4. Document Ranking](#4-document-ranking)
    - [4.1 Global explanations](#41-global-explanations)
    - [4.2 Local explanations](#42-local-explanations)
  - [5. Retrieval Augmented Generation (RAG)](#5-rag-explanations)
    - [5.1 Faithfulness and Attributions in RAG](#51-faithful-attributions-rag)
    - [5.2 Knowledge Conflicts in RAG](#52-knowledge-conflicts-rag)
- [🛠️ Tools & Libraries](#️-tools--libraries)
- [👏 Welcome to discussion (Contributing)](#-welcome-to-discussion-contributing)

---

## 📖 Cite Our Work
If you find our survey or this repository helpful in your research, please consider citing our paper:
```bibtex
@article{saha2024explainability,
  author = {Saha, Sourav and Majumdar, Debapriyo and Mitra, Mandar},
  title = {Explainability of Text Processing and Retrieval Methods: A Survey},
  year = {2024},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  journal = {ACM Computing Surveys},
  url = {[https://doi.org/10.1145/3801957](https://doi.org/10.1145/3801957)},
  doi = {10.1145/3801957}
}
