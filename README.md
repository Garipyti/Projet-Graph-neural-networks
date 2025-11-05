# Projet-Graph-neural-networks
# Graph Neural Networks (GNNs): Property Prediction on the ZINC Dataset

**Difficulty**: medium

## Overview

This project is an exploration of **Graph Neural Networks (GNNs)**, a specialized class of deep learning models designed to operate on non-Euclidean data structures (graphs). The project aims to cover the fundamental concepts of graph theory, GNN mechanics, and their application to a real-world problem: predicting molecular properties using the **ZINC chemical compounds dataset** via the **PyTorch Geometric** library.

## Objectives

1. **Grasp and Document Graph Fundamentals:**
  * Explain the concept of a **graph** mathematically, including the roles of **nodes (vertices)** and **edges**.
  * Introduce GNNs, detailing how their operation differs from traditional neural networks (e.g., CNNs or MLPs) and their key applications.

2. **Explain Graph Operations:**
  * Detail **Graph Convolution**, explaining how it generalizes the concept of convolution from a grid (image) to an irregular graph structure (message passing).
  * Detail **Graph Pooling** (e.g., global or hierarchical pooling) and its importance for summarizing graph-level features while reducing complexity.

3. **PyTorch Geometric Implementation on ZINC:**
  * Utilize the **PyTorch Geometric** library to construct and train a GNN model on the **ZINC dataset**.
  * Design a network architecture suitable for the task of chemical property prediction (a regression task on ZINC).

4. **Performance Evaluation:**
  * Evaluate the GNN model's predictive accuracy on the test set, using appropriate metrics for the regression task (e.g., Mean Absolute Error or Root Mean Squared Error).

5. **Advanced Exploration (Optional):**
  * Implement a **Graph Transformer** model from scratch, referencing the provided research paper.
  * Compare the performance, computational characteristics, and architectural differences of the Graph Transformer model against the standard GNN model.

## Expected Deliverables

1. **Codebase:** Complete, well-documented Python code for the GNN model using PyTorch Geometric and the ZINC dataset. Include the optional implementation of a Graph Transformer model, if completed.
2. Documentation:
  - `README.md`: A summary of the project’s objectives, methodology, and outcomes.
  - `REPORT.md`: A detailed report explaining the theoretical aspects of VAEs, the mathematical foundation of ELBO, and practical applications.

## Resources and References

* **Graph Transformer Paper:** https://proceedings.neurips.cc/paper_files/paper/2019/file/9d63484abb477c97640154d40595a3bb-Paper.pdf
* **ZINC Dataset Documentation (PyG):** https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.ZINC.html
* **PyTorch Geometric GitHub:** https://github.com/pyg-team/pytorch_geometric
* **Review on Graph Neural Networks:** https://arxiv.org/pdf/1812.08434.pdf
