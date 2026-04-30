**Predictive Maintenance for Industrial Milling Machines Using Deep Learning-Based Anomaly Detection**

<img width="1536" height="1024" alt="Predictive Maintenance for Industrial Milling Machines" src="https://github.com/user-attachments/assets/e8807c9e-d56a-47de-9dde-dfb6275b8a5f" />

# Predictive Maintenance for Industrial Milling Machines

## 📌 Project Overview

This project develops a deep learning-based predictive maintenance system for industrial milling machines to predict equipment failures before they occur. The system employs LSTM networks and Autoencoder architectures to classify failure types and detect anomalies in real-time operations.

The model identifies five distinct failure modes:

* Tool Wear Failure
* Heat Dissipation Failure
* Power Failure
* Overstrain Failure
* Random Failure

By implementing this predictive approach, manufacturing facilities can transition from reactive maintenance to proactive intervention, reducing unplanned downtime and extending equipment lifespan.

This project demonstrates the application of deep learning in **Industry 4.0** and **Digital Twin** concepts, where real-time sensor data enables intelligent decision-making for maintenance scheduling and operational efficiency.

---

## 🚀 How to Run the Project

The complete implementation is provided in a single Google Colab notebook:

📂 **Path:** `notebook/Predictive Maintenance for Industrial Milling Machines.ipynb`

### Steps to execute:

1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Ensure required libraries are installed (handled in notebook)

---

## 📊 Experiment Tracking (WandB)

This project uses **Weights & Biases (WandB)** for experiment tracking.

### 🔹 Option 1: View Results (Recommended)

You can directly view experiment results here:
👉 *[Add your WandB project link here]*

(No API key required)

---

### 🔹 Option 2: Run with WandB Logging

To enable logging:

```python
import os
os.environ["WANDB_API_KEY"] = "your_wandb_api_key"
```

⚠️ **Important:**

* Do NOT share your API key publicly
* If not provided, the project will still run without logging

---

## 📁 Repository Structure

```
├── notebook/
│   └── Predictive Maintenance for Industrial Milling Machines.ipynb
├── figures/
├── README.md
```

---

## 📌 Notes

* The Autoencoder model is robust to class imbalance and performs effective anomaly detection
* Hyperparameter experiments are tracked using WandB
* Designed for reproducibility and easy experimentation

---

