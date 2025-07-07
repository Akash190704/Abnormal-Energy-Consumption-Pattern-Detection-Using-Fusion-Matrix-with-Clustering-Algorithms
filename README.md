# Abnormal Energy Consumption Pattern Detection Using Fusion Matrix with Clustering Algorithms

This project aims to detect abnormal energy consumption patterns using a **Fusion Matrix** approach integrated with **unsupervised clustering algorithms** like K-Means, DBSCAN, and Hierarchical Clustering. The goal is to identify potential energy theft, unusual spikes, or operational faults in smart grid data.

## 📌 Objective

To develop a system that:
- Analyzes smart meter data
- Applies clustering algorithms for anomaly detection
- Combines results using a fusion matrix to improve accuracy and reduce false positives

## Techniques Used

- **Data Preprocessing**: Handling missing values, normalization
- **Clustering Algorithms**:
  - K-Means Clustering
  - DBSCAN
  - Hierarchical Clustering
- **Fusion Matrix**: Aggregates the decisions of individual clustering models
- **Anomaly Scoring**: Abnormality ranked based on consensus among algorithms

## 🗃️ Dataset

The project uses energy consumption datasets from:
- Public smart meter datasets (e.g., UCI Machine Learning Repository or Smart* datasets)
- Simulated or synthetically generated data for testing

> Dataset files should be placed in the `/data` folder.



