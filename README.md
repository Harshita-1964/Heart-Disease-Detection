# Heart Disease Detection Using CNN-LSTM

This project focuses on detecting heart disease from phonocardiogram (PCG) signals using a hybrid Deep Learning architecture that combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The model is trained on the PhysioNet/CinC 2016 dataset and achieves high performance in classifying heart sound recordings into normal or abnormal classes.

---

## 📁 Dataset

- **Source**: [PhysioNet/CinC 2016 Challenge](https://physionet.org/content/challenge-2016/1.0.0/)
- Contains heart sound recordings labeled as **Normal** or **Abnormal**.

---

## ⚙️ Methodology

1. **Data Preprocessing**:
   - PCG recordings were converted into spectrograms using time-frequency transformation.
   - Standardization and augmentation techniques were applied.

2. **Model Architecture**:
   - CNN layers for spatial feature extraction.
   - LSTM layers to capture temporal dependencies in heartbeat rhythms.
   - Dense layers for final classification.

3. **Training**:
   - Optimizer: Adam
   - Loss Function: binary_crossentropy
   - Epochs: 100
   - Batch Size: 32

---

## 📊 Results

- **Accuracy**: 81%
- **Evaluation Metrics**:
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC
  - Matthews Correlation Coefficient
  - TPR
  - FPR
  - Specificity
  - NPV
  - Confusion Matrix
  - Training/Validation Loss & Accuracy Plots

---

## 📌 Highlights

- Developed a hybrid CNN-LSTM model tailored for PCG signal classification.
- Leveraged time-frequency domain features using spectrograms.
- Documented and visualized results via Jupyter Notebook.

---


