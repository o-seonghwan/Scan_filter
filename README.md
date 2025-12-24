# Clustering-Based Defense Against Adversarial Attacks on Event-Based Vision Data

This repository contains the official implementation of the graduation thesis: **"Clustering-Based Defense Against Adversarial Attacks on Event-Based Vision Data"**.

We propose a robust defense mechanism utilizing **DBSCAN clustering** to filter out adversarial noise (e.g., Dash Attack, MF-Aware Dash Attack) from N-MNIST event streams, preserving the classification performance of Spiking Neural Networks (SNNs).

## 📌 Key Features
- **Attack Simulation:** Implementation of *Dash Attack* and *MF-Aware Dash Attack* on event data.
- **Defense Mechanism:** A clustering-based filter (DBSCAN) that distinguishes between authentic event streams and adversarial noise based on spatiotemporal density.
- **Performance Analysis:** Evaluation of defense robustness under varying attack parameters.

## 🛠️ Requirements
This project is implemented in **Python 3.x**. The main dependencies are:
- `numpy`
- `torch` (or `tensorflow` depending on your backend)
- `scikit-learn` (for DBSCAN)
- `matplotlib` (for visualization)

To install the dependencies, run:
```bash
pip install -r requirements.txt
