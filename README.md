## Signal Preprocessing and Deep Residual Learning for Improved Arrhythmia Detection: A 1D ResNet Approach

### 📌 Overview

This project aims to develop an automated system for detecting and classifying arrhythmias using deep learning. We employ a customized 1D ResNet (Residual Neural Network) model to classify ECG signals into multiple arrhythmia types. The model is designed for high accuracy, fast inference, and real-time deployment capabilities.

---

### 🎯 Objectives

- To preprocess ECG signals and remove noise for reliable analysis.
- To segment ECG signals and extract meaningful features.
- To design a 1D ResNet architecture for accurate classification of arrhythmia types.
- To evaluate the model using precision, recall, F1-score, and confusion matrix.
- To compare the model’s performance with existing state-of-the-art methods.

---

### 🧠 Methodology

#### 1. **Signal Preprocessing**
- Applied bandpass filtering to remove noise and baseline wander.
- Normalized ECG amplitudes for consistent input scale.

#### 2. **Segmentation**
- Identified R-peaks to segment the ECG signal into individual heartbeats.
- Focused on extracting QRS complexes for accurate diagnosis.

#### 3. **Model Architecture**
- Implemented a 1D ResNet model using residual blocks.
- Optimized using techniques like dropout, batch normalization, and adaptive learning rate.

#### 4. **Training & Evaluation**
- Trained on the MIT-BIH Arrhythmia dataset.
- Evaluated using accuracy, precision, recall, and F1-score.
- Achieved >95% classification accuracy.

---

### 🗃 Dataset

- **MIT-BIH Arrhythmia Database**
- 109,446 ECG samples at 125 Hz sampling rate
- Includes various heartbeat types labeled according to AAMI standards

Dataset Link :- https://drive.google.com/drive/folders/1oOSTojQ2cIe1xMEHcPkkZUNcYj72npL1?usp=sharing

---

### ⚙️ Tools & Technologies

- Python
- TensorFlow / PyTorch
- NumPy, Pandas, Matplotlib
- Google Colab (TPU/GPU Support)

---

### 📈 Results

- Accuracy: >95% across all arrhythmia classes
- Robust performance under noise and class imbalance
- Efficient real-time signal processing with low computational overhead

---

### 🔍 Future Work

- Extend model to handle multi-lead ECG signals
- Real-time integration with wearable devices
- Improved interpretability with attention mechanisms or explainable AI (XAI)

---

### 👨‍💻 Team Members

- Prajwal Santosh Lonari (121B1B146)  
- Soham Yuvraj Ovhal (121B1B166)  
- Nitin Baskar Pandita (121B1B170)  
- Ritesh Atul Parhate (121B1B172)

---

### 🧑‍🏫 Guided By

**Dr. Ketan Desale**  
Department of Computer Engineering  
PCCoE, Pune

---
