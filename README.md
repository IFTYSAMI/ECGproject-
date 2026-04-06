# 🫀 ECG Arrhythmia Classification using CNN

## 📌 Project Overview
This project applies Machine Learning and Deep Learning models to classify ECG signals and detect arrhythmia. A comparison between traditional ML models and a 1D Convolutional Neural Network (CNN) is performed.

---

## 🧠 Models Used
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting
- 1D Convolutional Neural Network (CNN)

---

## 📊 Results Summary

| Model | Accuracy (%) | Type |
|------|-------------|------|
| 1D-CNN | **99.65** | Deep Learning |
| Gradient Boost | 95.63 | Machine Learning |
| Random Forest | 95.15 | Machine Learning |
| SVM (RBF) | 94.33 | Machine Learning |
| KNN | 89.95 | Machine Learning |

---

## 🔍 Key Insights
- CNN achieved the highest accuracy (99.65%)
- Deep learning performs better for ECG time-series data
- Traditional ML models require manual feature engineering

---

## 📈 Visual Results

### 📊 Model Comparison (ML Models)
![ML Comparison](ecg_results/fig3_ml_comparison.png)

### 🧠 Confusion Matrix (Gradient Boost)
![GB Confusion Matrix](ecg_results/fig4_ml_confusion_matrix.png)

### 📉 CNN Training Loss
![Loss Curve](ecg_results/fig7_cnn_loss.png)

### 📈 CNN Training Accuracy
![Accuracy Curve](ecg_results/fig8_cnn_accuracy.png)

### 🧠 Confusion Matrix (1D-CNN)
![CNN Confusion Matrix](ecg_results/fig9_cnn_confusion_matrix.png)

### 🎯 ROC Curve (1D-CNN)
![ROC Curve](ecg_results/fig10_cnn_roc.png)

### 🏆 Final Model Comparison (ML vs CNN)
![Final Comparison](ecg_results/fig11_all_models_comparison.png)
---

## 📂 Project Structure
- `cnn-keras-1.ipynb` → Model implementation
- `summary_table.csv` → Model comparison
- `ecg_results/` → Output graphs

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook