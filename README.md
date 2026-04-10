# Attention-Enhanced-Few-Shot-CNN-Autoencoder-for-Anomaly-Detection-DL-ASSIGNMENT



## 🚀 Overview

This project presents an **Attention-Enhanced CNN Autoencoder** designed for anomaly detection in images under **few-shot learning conditions**. The model learns normal patterns and detects anomalies using reconstruction error.

Unlike traditional autoencoders, this approach integrates an **attention mechanism** to improve feature representation and anomaly localization.

---

## 🎯 Objectives

* Learn normal image patterns using an autoencoder
* Detect anomalies via reconstruction error
* Improve performance using **attention mechanism**
* Work effectively with **limited (few-shot) data**

---

## 🧠 Key Features

* ✅ CNN-based Autoencoder
* ✅ Attention Mechanism (novel contribution)
* ✅ Few-shot learning setup
* ✅ Reconstruction-based anomaly detection
* ✅ Heatmap visualization for anomaly localization

---

## 🏗️ Model Architecture

```
Input Image
   ↓
CNN Encoder
   ↓
Attention Block
   ↓
Latent Representation
   ↓
CNN Decoder
   ↓
Reconstructed Image
```

---

## ⚙️ Tech Stack

* Python 🐍
* PyTorch 🔥
* Torchvision
* Matplotlib

---

## 📂 Dataset

* CIFAR-10 (used for demonstration)
* Few-shot subset (limited samples)

You can replace with:

* MVTec AD (industrial anomaly detection)
* Custom datasets

---

## 🧪 Training Details

* Optimizer: Adam
* Loss Function: Mean Squared Error (MSE)
* Epochs: 5
* Batch Size: 32

---

## 📊 Evaluation Method

* Reconstruction Error (MSE)
* Threshold-based anomaly detection

### 🔍 Anomaly Detection Logic

```
If reconstruction error > threshold → Anomaly
Else → Normal
```

---

## 🔥 Results

* Model successfully reconstructs normal images
* Anomalies show **high reconstruction error**
* Heatmaps highlight anomaly regions

---

## 🌟 Novelty

This project introduces:

* Attention-enhanced reconstruction
* Improved anomaly localization
* Better performance in **low-data scenarios**

---

## 📸 Output Visualization

* Original vs Reconstructed Images
* Reconstruction Error Heatmap

---

## 📈 Future Work

* Integrate GAN for sharper outputs
* Use SSIM / Perceptual Loss
* Apply on real-world datasets (MVTec AD)
* Add ROC-AUC evaluation

---

## 📦 How to Run

```bash
# Clone repo
git clone https://github.com/your-username/anomaly-detection-autoencoder.git

# Install dependencies
pip install torch torchvision matplotlib

# Run notebook
jupyter notebook
```

---

## 👨‍💻 Author

**Rishi Walia**
B.Tech AI & ML
VIT

---

## 📜 License

This project is for academic purposes.
