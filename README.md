# 🩺 A Weighted Multimodal Deep Learning Ensemble Framework for Breast Cancer Detection

## 📌 Overview

This project proposes a **Weighted Multimodal Deep Learning Ensemble Framework** for breast cancer detection by integrating information from **mammography** and **ultrasound imaging**. Instead of relying on a single imaging modality, the framework trains modality-specific Convolutional Neural Networks (CNNs) independently and combines their predictions using **weighted decision-level fusion** to improve diagnostic reliability and reduce false negatives.

The objective is to enhance early breast cancer detection by leveraging complementary information from both imaging modalities while maintaining high sensitivity and classification performance.

---

## 🎯 Problem Statement

Traditional breast cancer diagnosis often relies on a single imaging modality, which may miss important diagnostic information.

- Mammograms provide excellent structural information but can struggle with dense breast tissue.
- Ultrasound images capture soft tissue characteristics but are affected by speckle noise and operator variability.

This project combines both modalities using an ensemble strategy to produce more robust and reliable predictions.

---

## 🚀 Key Features

- ✅ Multimodal breast cancer diagnosis
- ✅ Separate CNN models for mammogram and ultrasound images
- ✅ Weighted decision-level ensemble fusion
- ✅ Image preprocessing and normalization
- ✅ Data augmentation for improved generalization
- ✅ Grad-CAM visualization for model explainability
- ✅ Reduced false negatives for improved clinical reliability

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Deep Learning
- Convolutional Neural Networks (CNNs)
- Mammography Imaging
- Ultrasound Imaging
- Ensemble Learning
- Grad-CAM
- NumPy
- Matplotlib
- Scikit-learn

---

## 🏗️ Methodology

1. Collect mammogram and ultrasound datasets.
2. Preprocess images through normalization and augmentation.
3. Train separate CNN models for each modality.
4. Extract modality-specific features.
5. Generate prediction probabilities from each model.
6. Combine predictions using weighted ensemble fusion.
7. Produce the final benign/malignant classification.

---

## 📊 Performance

| Model | Accuracy | Recall | Precision | F1 Score |
|---------|----------|----------|-----------|----------|
| Ultrasound CNN | 77.55% | 87.50% | 60.87% | 71.79% |
| Mammogram CNN | 93.63% | 95.83% | 94.72% | 95.27% |
| **Weighted Ensemble** | **92.86%** | **100.00%** | **82.05%** | **90.14%** |

The ensemble model achieved perfect recall on the evaluated dataset, demonstrating its ability to minimize missed malignant cases.

---

## 📈 Explainable AI

To improve interpretability, **Grad-CAM** visualizations are used to highlight image regions influencing the model's predictions. This helps verify that the network focuses on clinically relevant tumor regions and increases trust in AI-assisted diagnosis.

---

## 📂 Project Structure

```
project/
│── code/
│── dataset/
│── documentation/
│── models/
│── notebooks/
│── README.md
```

---

## 🏥 Applications

- Breast cancer screening
- Computer-aided diagnosis (CAD)
- Clinical decision support systems
- AI-assisted radiology
- Medical image analysis research

---

## 🔮 Future Scope

- Expand to larger and more diverse datasets.
- Improve multimodal fusion strategies.
- Integrate additional imaging modalities.
- Deploy as a clinical decision-support tool.
- Optimize models for real-time hospital applications.

---

## 👨‍💻 Author

**Vemula Pramod**

Department of Computer Science  
Vellore Institute of Technology

---

## 📜 License

This repository is intended for educational and research purposes.
