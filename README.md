# Comparison of Long-Lived Bug Prediction in FLOSS Using BERT, TF-IDF, GNN, and RNN

## Overview
This repository presents an empirical study on long-lived bug prediction in Free/Libre and Open-Source Software (FLOSS) projects, comparing the efficacy of four machine learning approaches: BERT (transformer-based), TF-IDF (bag-of-words), GNN (Graph Convolutional Networks), and RNN (Recurrent Neural Networks). The project evaluates feature extraction techniques and classifiers (e.g., MLPClassifier, MultinomialNBClassifier) on FLOSS datasets, demonstrating BERT's superior performance (especially with DistilBERT) in accuracy and bug severity prediction. This work aims to enhance software quality assurance and optimize development practices in open-source ecosystems.

The study was conducted as part of an M.Tech thesis at Jawaharlal Nehru Technological University-Gurajada (2024), guided by Dr. B. Tirimula Rao. It provides insights for ML-driven bug prediction, with potential applications in CI/CD pipelines and software engineering.

## Key Contributions
- **Methodology**: Investigated feature extraction (BERT, TF-IDF, GCN, RNN) and classifiers for bug severity prediction in FLOSS repositories.
- **Results**: BERT-based models (e.g., DistilBERT + MLPClassifier) outperformed TF-IDF, GCN, and RNN, achieving higher precision/recall on diverse datasets.
- **Impact**: Improves bug detection efficiency, reducing long-lived bugs in open-source projects.

## Repository Structure
- `bug_prediction_notebook.ipynb`: Jupyter notebook with data loading, feature extraction, model training, and evaluation.
- `data/`: Sample FLOSS datasets (e.g., bug reports from GitHub repos; anonymized for privacy).
- `models/`: Trained models and feature extractors (BERT, TF-IDF, GNN, RNN).
- `results/`: Plots and metrics (accuracy, F1-score, confusion matrices).
- `requirements.txt`: Dependencies for reproducibility.
- `evaluation.py`: Script for running experiments and generating reports.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/pradeepdegalaroyal/Comparison-of-Long-lived-Bug-Prediction-in-FLOSS-using-BERT-TF-IDF-GNN-and-RNN.git
   cd Comparison-of-Long-lived-Bug-Prediction-in-FLOSS-using-BERT-TF-IDF-GNN-and-RNN
2. pip install -r requirements.txt
3. jupyter notebook bug_prediction_notebook.ipynb


2.Citation
If using this work, cite:
Degala Royal, P. (2024). Enhancing Long-lived Bug Prediction in FLOSS: An Empirical Comparison of BERT, TF-IDF, GCN, and RNN. M.Tech Thesis, JNTU-Gurajada.
