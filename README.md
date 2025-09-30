# Multi-Feature Extraction System for Orthophoto Analysis Using Deep Neural Networks

## 📌 Overview

This project presents a **ResUNet-based multi-class semantic segmentation system** designed for **high-resolution drone orthophotos**. The system enables automated, accurate extraction of rural land features such as **building footprints** and **road networks**, optimized for scalability and deployment in real-world mapping initiatives like **SVAMITVA**.

Unlike conventional methods relying on manual digitization or generic CNN/U-Net models, our approach introduces **residual identity blocks within a U-Net encoder-decoder framework**, combined with a **custom Tversky loss function**, delivering superior accuracy in **heterogeneous rural landscapes**.

---

## 🚀 Key Features

* **ResUNet Architecture**: Residual identity blocks enhance training stability and allow deeper learning while mitigating vanishing gradients.
* **Custom Loss Function**: Tversky loss effectively handles severe **class imbalance** (small building footprints and roads vs. large background areas).
* **High-Resolution Processing**: Inputs are normalized into **512×512 pixel patches**, enabling fine-grained boundary detection.
* **Cloud Scalability**: Architecture supports large-scale orthophoto datasets for rural mapping.
* **Multi-Class Segmentation**: Extracts **buildings, roads**, and can be extended to other rural features with retraining.

---

## 🧠 Research Background

* Traditional methods: Classical image processing, manual digitization — **time-consuming** and **error-prone**.
* CNNs/U-Net: Improved segmentation but limited performance on rural datasets due to **heterogeneity** and **class imbalance**.
* Our approach: Integrates **ResUNet + Tversky Loss + High-Resolution Upsampling**, specifically adapted to **rural orthophotos** for **superior precision and scalability**.


