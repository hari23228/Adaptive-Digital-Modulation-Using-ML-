<h1 align="center">📶 Adaptive Digital Modulation using ML</h1>
<h3 align="center">Real-time Smart Switching between BPSK & QPSK using Machine Learning</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/GNU%20Radio-6F2DA8?style=for-the-badge&logo=gnuradio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-00BCD4?style=for-the-badge&logo=TensorFlow&logoColor=white"/>
  <img src="https://img.shields.io/badge/IoT-FF5722?style=for-the-badge&logo=internetofthings&logoColor=white"/>
</p>

---

## 📌 Overview

This project implements an **adaptive digital modulation** system that dynamically switches between **BPSK and QPSK** based on real-time channel conditions. It uses **Machine Learning** models trained on features like **SNR**, **BER**, and **Phase Spread** and integrates with **GNU Radio** for live operation — perfect for IoT and wireless systems.

---

## 💡 Key Features

- 🔁 Real-time modulation switching (BPSK/QPSK)
- 🧠 ML-powered decision-making with KNN, MLP & Logistic Regression
- 📶 Feature extraction: SNR, BER, Phase Spread
- 🧪 Noise simulation for robust model training
- 📊 Visual comparison of model performance

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python | Model training & data processing |
| 📡 GNU Radio | Signal generation, modulation, real-time switching |
| 🔬 Scikit-learn | ML model training (KNN, MLP, Logistic Regression) |
| 📄 CSV | Dataset generation and model input |
| 📈 Matplotlib | Model performance visualization |

---

## 🧠 ML Models Used

- **Logistic Regression**: Fast baseline for binary classification
- **K-Nearest Neighbors (KNN)**: Best accuracy and chosen for deployment
- **Multi-Layer Perceptron (MLP)**: Handles complex, nonlinear boundaries

---

## 🔁 Dataflow

```text
Random Source ➡️ Modulator (BPSK/QPSK)
                ➡️ Noise Block ➡️ Feature Extraction ➡️
                ➡️ ML Modulation Switch ➡️ Output
