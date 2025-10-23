# Applied Machine Learning for Identifying Malicious Sensor Nodes

This project applies machine learning and big data analytics to detect malicious nodes in wireless sensor networks (WSNs). Traditional intrusion detection and prevention systems often struggle with false positives, evolving attack patterns, and rule-based limitations. This work explores how AI-driven approaches can enhance network security by detecting anomalous behaviors more accurately.

## Overview

Malicious nodes can degrade network performance by increasing packet error rates, power consumption, and request frequencies. This project leverages AI models trained on the SensorNetGuard dataset
 to identify such anomalies efficiently.

## Methods

The workflow includes:

Data Consolidation: Integration of network, power, and behavioral metrics.

Data Preprocessing & Exploration: Cleaning, normalization, and visualization of network metrics.

Modeling & Evaluation: Testing multiple ML models for classification and anomaly detection.

## Models Implemented

Logistic Regression – Supervised learning for binary classification.

Isolation Forest – Tree-based anomaly detection.

DBSCAN – Density-based clustering for unsupervised anomaly detection.

Support Vector Machine (SVM) – Hyperplane-based classification.

## Key Findings

DBSCAN and Logistic Regression performed best overall.

DBSCAN showed superior robustness in real-world conditions with multiple attackers.

Integration of AI models with traditional IDS/IPS systems can significantly improve detection accuracy.

## Tech Stack

Python (scikit-learn, pandas, NumPy, matplotlib)

Jupyter Notebook / Google Colab

Dataset: SensorNetGuard IEEE Dataport

## Author

Pawat Songkhopanit (633 81555 21) - Chulalongkorn University
Big Data and Artificial Intelligence
