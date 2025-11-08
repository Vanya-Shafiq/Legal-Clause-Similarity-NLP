# Legal Clause Similarity NLP

This project implements baseline NLP models to determine semantic similarity between legal clauses.  
It focuses on identifying whether two clauses convey the same legal principle or related meaning.

## Features
- **Models Implemented**:
  - BiLSTM Siamese Network
  - Attention-based Encoder
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-Score
  - ROC-AUC
  - Training Time Comparison
- **Visualizations**:
  - Training & validation accuracy/loss curves
  - ROC curves
  - Examples of correctly and incorrectly matched clauses

## Dataset
- Uses the [Legal Clause Dataset](https://www.kaggle.com/bahushruth/legalclausedataset)  
- CSV files categorized by clause type (e.g., acceleration, access-to-information, accounting-terms)
