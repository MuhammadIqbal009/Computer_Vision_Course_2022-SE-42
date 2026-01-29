# 🫀 PhysioNet ECG Image Digitization  
**Computer Vision Course Assignment**

This repository contains my solution for the Kaggle competition:  
**PhysioNet ECG Image Digitization Challenge**

The task is to convert ECG images into digitized ECG signals using computer vision and deep learning.

---

## 🎯 Project Goal

- Take ECG images as input  
- Detect and segment waveform regions  
- Extract ECG signal traces  
- Convert them into digital time-series format  
- Generate output in Kaggle submission structure  

---

## 🧠 Method Overview

This solution uses a **multi-stage deep learning pipeline**:

### 🔹 Stage 0 – Image Preprocessing  
Enhances ECG image quality and prepares it for segmentation.

### 🔹 Stage 1 – Waveform Segmentation  
A segmentation model detects ECG signal regions.

### 🔹 Stage 2 – Signal Extraction  
Segmented waveforms are converted into 1D digital signals and aligned properly.

### 🔹 Source Classifier (EfficientNet-B2)  
Predicts ECG image source type to apply better preprocessing and improve segmentation quality.

---

## 🏗️ Models Used

| Component | Model |
|----------|------|
| Source Classifier | EfficientNet-B2 |
| Stage 1 | Segmentation Network |
| Stage 2 | Signal Reconstruction Network |

---

## Kaggle Performance

## 🏆 Kaggle Competition Score

Below is the score achieved in the **PhysioNet ECG Image Digitization** competition:

<p align="center">
  <img src="Assets/PhysioNet%20Kaggle.png" alt="Kaggle Score Screenshot" width="800"/>
</p>

**Public Leaderboard Score:** **18.08321**

---

## Technical Stack

- Python  
- PyTorch  
- OpenCV  
- NumPy / Pandas  
- Signal Processing Techniques  

---

---

## Academic Context

This work was completed as part of a Computer Vision course assignment, integrating:

Deep learning for medical imaging

Image segmentation

Signal processing

Real-world Kaggle competition workflow

---

## Author

Saqlain Mushtaq 2022-SE-33

Muntazir Mehdi 2022-SE-37

Muhammad Iqbal 2022-SE-42

---
