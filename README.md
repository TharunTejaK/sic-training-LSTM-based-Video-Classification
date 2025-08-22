# 🎥 LSTM-based Video Classification

This project implements a **video classification model** using **Long Short-Term Memory (LSTM)** networks. The model extracts frame-level features from videos and learns temporal dependencies to classify them into categories.

---

## 📌 Project Overview
Video classification is an important task in computer vision where the goal is to assign a label to a sequence of video frames. Unlike static images, videos carry **temporal information**, making LSTMs a suitable choice as they can capture sequence dependencies.

In this project:
- Extracted frames from videos.
- Preprocessed frames (resizing, normalization).
- Used feature extraction (CNN-based embeddings).
- Trained an **LSTM model** on the extracted sequence features.
- Evaluated the performance on test data.

---

## ⚙️ Features
- Frame preprocessing and sequence handling.
- LSTM model architecture for sequence classification.
- Training with labeled video data.
- Model evaluation with accuracy metrics.

---

## 📂 Project Structure
📁 LSTM_Video_Classification
│── 📓 Main
│── 📁 data/ # Dataset (videos/frames)
│── 📁 models/ # Saved trained models
│── 📁 outputs/ # Logs, results, and plots
│── README.md # Project documentation

---

## 🛠️ Installation & Requirements
Make sure you have Python 3.8+ installed. Install dependencies with:

```bash
pip install -r requirements.txt
