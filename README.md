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


<div align="center">
  <a href="taxonomy.pdf" target="_blank">
    <img src="taxonomy.jpg" alt="Taxonomy of Explainable Text Processing and Retrieval Methods" width="100%">
  </a>
  <p><em>Fig 1. Taxonomy of Explainable Text Processing and Retrieval Methods. (Click the image to view the high-res PDF)</em></p>
</div>

---

## 📖 Cite Our Work
If you find our survey or this repository helpful in your research, please consider citing our paper:
```bibtex
@article{10.1145/3801957,
author = {Saha, Sourav and Majumdar, Debapriyo and Mitra, Mandar},
title = {Explainability of Text Processing and Retrieval Methods: A Survey},
year = {2026},
issue_date = {August 2026},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {58},
number = {11},
issn = {0360-0300},
url = {https://doi.org/10.1145/3801957},
doi = {10.1145/3801957},
journal = {ACM Comput. Surv.},
month = may,
articleno = {284},
numpages = {48},
keywords = {Explainability, interpretability, text processing, information retrieval, natural language processing, machine learning}
}
```
# 📑 PaperList

## 1. Categorising Explanation Methods

## 2. Basic Methods for Constructing Post-hoc Explanations

## 3. Evaluating explanations

## 4. Document Ranking

### 4.1 Global explanations

- **Term Weighting Revisited (Singhal).**
  
  Thesis 1997. [[Paper](https://ecommons.cornell.edu/server/api/core/bitstreams/ac2f078e-3307-454f-89dc-26693c44b4f3/content)]

- **The importance of length normalization for XML retrieval (Kamps et al.).**
  
  IR Journal 2005. [[Paper](https://doi.org/10.1007/s10791-005-0750-7)]

- **An investigation of dirichlet prior smoothing’s performance advantage (Smucker and Allan).**
  
  Technical Report 2025. [[Paper](https://maroo.cs.umass.edu/getpdf.php?id=694)]

- **A Formal Study of Information Retrieval Heuristics (Fang et al.).**
  
  SIGIR 2004. [[Paper](https://doi.org/10.1145/1008992.1009004)]

- **Diagnostic Evaluation of Information Retrieval Models (Fang et al.).**
  
  TOIS 2011. [[Paper](https://doi.org/10.1145/1961209.1961210)]

- **Axiomatic Result Re-Ranking (Hagen et al.).**
  
  CIKM 2016. [[Paper](https://doi.org/10.1145/2983323.2983704)]

- **An Axiomatic Approach to Diagnosing Neural IR Models (Rennings et al.).**
  
  ECIR 2020. [[Paper](https://doi.org/10.1007/978-3-030-15712-8_32)]

- **Diagnosing BERT with Retrieval Heuristics (Camara and Hauff).**
  
  ECIR 2020. [[Paper](https://doi.org/10.1007/978-3-030-45439-5_40)]



### 4.2 Local explanations

- **LIRME: Locally Interpretable Ranking Model Explanation (Verma and Ganguly).**
  
  SIGIR 2019. [[Paper](https://doi.org/10.1145/3331184.3331377)]

- **EXS: Explainable Search Using Local Model Agnostic Interpretability (Singh and Anand).**
  
  WSDM 2019. [[Paper](https://doi.org/10.1145/3289600.3290620)]

- **A Study on the Interpretability of Neural Retrieval Models Using DeepSHAP (Fernando et al.).**
  
  SIGIR 2019. [[Paper](https://doi.org/10.1145/3331184.3331312)]

- **Alignment rationale for query-document relevance (Kim et al.).**
  
  SIGIR 2022. [[Paper](https://doi.org/10.1145/3477495.3531883)]

- **Extractive explanations for interpretable text ranking (Leonhardt et al.).**
  
  TOIS 2023. [[Paper](https://doi.org/10.1145/3576924)]

- **Evaluating the explainability of neural rankers (Pandian et al.).**
  
  ECIR 2024. [[Paper](https://doi.org/10.1007/978-3-031-56066-8_28)]

- **Model agnostic interpretability of rankers via intent modelling (Singh and Anand).**
  
  FAT 2020. [[Paper](https://doi.org/10.1145/3351095.3375234)]

- **Listwise explanations for ranking models using multiple explainers (Lyu and Anand).**
  
  ECIR 2023. [[Paper](https://doi.org/10.1007/978-3-031-28244-7_41)]

- **Towards explainable search results: A listwise explanation generator (Yu et al.).**
  
  SIGIR 2022. [[Paper](https://doi.org/10.1145/3477495.3532067)]

- **Explain like i am BM25: Interpreting a dense model’s ranked-list with a sparse approximation (Llordes et al.).**
  
  SIGIR 2023. [[Paper](https://doi.org/10.1145/3539618.3591982)]

- **Shapley value based feature attributions for learning to rank (Chowdhury et al.).**
  
  ICLR 2025. [[Paper](https://openreview.net/forum?id=4011PUI9vm)]

- **Faithful listwise feature attribution explanations for ranking models (Heuss et al.).**
  
  SIGIR 2025. [[Paper](https://doi.org/10.1145/3726302.3729971)]


## 5. Retrieval Augmented Generation (RAG)

## 🛠️ Tools & Libraries

### 
- **ir_explain - A Python Library of Explainable IR Methods (Saha et al.).**
  
  SIGIR 2025. [[Paper](https://dl.acm.org/doi/10.1145/3726302.3730343)]

- **I-REX - An interactive tool built on top of Lucene, providing a systematic view into the inner workings of retrieval models (Roy et al.).**
  
  CIKM 2029. [[Paper](https://dl.acm.org/doi/10.1145/3357384.3357859)]

- **Captum - Model interpretability and understanding tool for PyTorch. (Kokhlikyan et al.).**
  
  ICLR 2021. [[Paper](https://arxiv.org/abs/2009.07896)] [[Library](https://github.com/meta-pytorch/captum)]

- **The Language Interpretability Tool: Extensible, Interactive Visualizations and Analysis for NLP Models. (Tenney et al.).**
  
  EMNLP 2020. [[Paper](https://aclanthology.org/2020.emnlp-demos.15/)] [[Library](https://pair-code.github.io/lit/)]
