# Data-Science-ERP

# Spatial Transcriptomics: Few-Shot Learning for Cell-Type Classification

This repository contains the code and pipeline that explores how spatial context influences model performance in cell-type classification under extreme data scarcity.

The project compares four model architectures:
- Logistic Regression (baseline)
- GraphSAGE
- Graph Attention Network (GAT)
- Transformer-GNN Hybrid (novel model)

Experiments were conducted using a publicly available human breast cancer spatial transcriptomics dataset. The models were evaluated under 1-shot, 5-shot and 10-shot conditions to simulate low-data scenarios.

