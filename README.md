# CSC2042S Assignment 3: Neural Networks (Fashion-MNIST)
**Student:** Owen Mboma
**Student Number:** MBMCHA003

---

## 1. Project Overview
This project optimizes a Multi-Layer Perceptron (MLP) in PyTorch to classify clothing items from the Fashion-MNIST dataset. It covers:
- **Task 1:** IDX binary file decoding, data standardisation (mean and std derived strictly from the 50,000 training images to avoid leakage), and DataLoader creation.
- **Task 2:** Baseline MLP architecture (`784 -> 128 -> 64 -> 10`) trained with Adam for 10 epochs.
- **Task 3:** Systematic 8-run hyperparameter optimisation experiment varying Optimiser (SGD vs. Adam), Learning Rate, and Batch Size (64 vs. 128).
- **Task 4:** Comparative analysis, convergence and overfitting loss curves, and confusion matrix error analysis.

---

## 2. Directory Structure & Submitted Files

```text
MBMCHA003/
├── CSC2042S_Assignment3_NeuralNetworks_2026.ipynb   # Main documented Jupyter Notebook with saved cell outputs
├── MBMCHA003_Report.pdf                             # Formal written report (five pages maximum)
├── MBMCHA003_Report.docx                            # Editable report document
└── README.md                                        # Setup and reproduction instructions