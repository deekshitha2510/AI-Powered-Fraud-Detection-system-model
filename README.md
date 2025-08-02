# 🔍 AI-Powered Fraud Detection System

## 🚀 Overview

Fraudulent financial transactions pose a growing threat in the digital economy. This project presents an innovative, **AI-powered fraud detection system** that leverages advanced machine learning techniques, graph theory, and quantum-inspired feature engineering to identify and prevent fraud in **real-time**.

💡 Unlike traditional rule-based systems, our solution is:
- Fast ⚡
- Robust 💪
- Explainable 🧠
- Innovative 🚀

---

## 🎯 Objective

- Detect fraudulent transactions with **high precision and recall**
- Maintain **real-time performance**
- Ensure **interpretability and robustness** through feature diversity
- Incorporate **novel features inspired by quantum computing and graph theory**

---
## 📚 Tech Stack

- Python
- Scikit-learn
- LightGBM
- NetworkX
- NumPy, Pandas
- Matplotlib/Seaborn (for visualization)

---
## 📊 Dataset & Preprocessing

- Dropped redundant fields like `zipcodeOri`, `zipMerchant`
- Encoded categorical fields (`gender`, `category`) using `LabelEncoder`
- Extracted time features and filled missing values with 0

---

## 🧪 Feature Engineering

### 🔮 Quantum-Inspired Features
- Quantum Amplitude Encoding
- Entanglement-Inspired Features
- Superposition States
- Interference Patterns

### 🕵️ Behavioral Patterns
- Risk profiles for customers and merchants
- Transaction vs. average spending comparison

### 📆 Temporal Indicators
- Weekend detection
- Time since last transaction

### 🌐 Graph Features
- Constructed bipartite graph using `NetworkX`
- Calculated centralities: **PageRank**, **Betweenness**
- Ego-graphs for visualizing fraud clusters

---

## 🧠 Model Architecture

### 🧬 Quantum-Inspired Autoencoder
- Learns normal transaction behavior from non-fraud data
- Uses **reconstruction error** as anomaly score

### 🌲 Graph-Based Isolation Forest
- Detects structural anomalies from graph centrality scores

### ⚡ LightGBM Gradient Boosting
- Robust, fast classifier trained on top-20 selected features

### 🔁 Stacking Ensemble
- Meta-model combines:
  - LightGBM prediction probabilities
  - Autoencoder reconstruction errors
  - Isolation Forest scores

---

## 📈 Evaluation Metrics

| Metric        | Score   |
|---------------|---------|
| Precision     | 0.9507  |
| Recall        | 0.9104  |
| F1 Score      | 0.9301  |
| AUC-ROC       | 0.9928  |

✔️ High AUC and balanced precision/recall reflect both **accuracy** and **practical effectiveness**.

---

## 📤 Output

Predictions are saved to `prediction.csv` including:
- `transaction_id`
- `is_fraud` (0 or 1)
- `fraud_probability`

---

## 🌟 Innovation Highlights

- ✨ Quantum-inspired feature transformations
- 🌐 Graph-based anomaly detection using centrality
- 🧠 Autoencoder-based novelty detection
- 🧩 Robust stacking ensemble for final prediction


