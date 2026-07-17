# 🩺 Fetal Plane Classification using VGG19 + MSCAM

Deep Learning-based fetal ultrasound plane classification using **VGG19** integrated with a **Multiscale Channel Attention Module (MSCAM)**. This project classifies fetal ultrasound images into six anatomical planes to support automated prenatal screening and improve diagnostic efficiency.

---

## 📌 Project Overview

Accurate identification of fetal ultrasound planes is an important step in prenatal diagnosis. Manual classification is time-consuming and depends on the expertise of sonographers.

This project implements a deep learning framework that combines **transfer learning (VGG19)** with a **Multiscale Channel Attention Module (MSCAM)** to improve feature extraction and classification performance on fetal ultrasound images.

---

## 🎯 Objectives

- Classify fetal ultrasound images into six anatomical planes.
- Improve feature learning using the MSCAM attention mechanism.
- Evaluate the model using multiple performance metrics.
- Visualize model performance through ROC curves, confusion matrix, and t-SNE.

---

## 🧠 Model Architecture

The proposed architecture consists of:

- Pretrained **VGG19** backbone
- Multiscale Channel Attention Module (MSCAM)
- Global Average Pooling
- Dense Layers
- Softmax Classification Layer

### Workflow

```
Ultrasound Image
        │
        ▼
 Image Preprocessing
        │
        ▼
   Pretrained VGG19
        │
        ▼
      MSCAM
        │
        ▼
Global Average Pooling
        │
        ▼
 Fully Connected Layer
        │
        ▼
 Softmax Classifier
```

---

## 📂 Dataset

The project uses the **Spanish Fetal Ultrasound Dataset** containing labeled fetal ultrasound images.

### Classes

- Fetal Abdomen
- Fetal Brain
- Fetal Femur
- Fetal Thorax
- Maternal Cervix
- Other

---

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn

---

## 🔬 Project Pipeline

1. Download and prepare dataset
2. Load metadata and image labels
3. Perform train-test split
4. Build TensorFlow data pipeline
5. Apply VGG19 preprocessing
6. Construct VGG19 + MSCAM model
7. Train the network
8. Evaluate performance
9. Generate visualizations
10. Predict new ultrasound images

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall (Sensitivity)
- F1 Score
- Matthews Correlation Coefficient (MCC)
- ROC Curve
- Area Under Curve (AUC)
- Confusion Matrix

---

## 📈 Visualizations

The notebook includes:

- Training Accuracy
- Training Loss
- Validation Accuracy
- Validation Loss
- Confusion Matrix
- ROC Curves
- t-SNE Feature Visualization
- Confidence Scores
- Sample Predictions

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Fetal-Ultrasound-Classification.git
cd Fetal-Ultrasound-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📁 Repository Structure

```
Fetal-Ultrasound-Classification/
│
├── README.md
├── requirements.txt
├── notebook/
│   └── VGG19_MSCAM_Fetal_Ultrasound.ipynb
│
├── images/
│
├── results/
│
└── models/
```

---

## 📚 Key Features

- Transfer Learning using VGG19
- Multiscale Channel Attention (MSCAM)
- Efficient TensorFlow data pipeline
- Multi-class ultrasound classification
- Comprehensive model evaluation
- Rich visual analytics

---

## 🔮 Future Improvements

- Hyperparameter optimization
- Explainable AI using Grad-CAM
- Real-time ultrasound classification
- Deployment as a web application
- Comparison with EfficientNet, ResNet, and Vision Transformers

---

## 👩‍💻 Author

**Vikhasini Sakthivel**

B.Tech Information and Communication Technology  
SASTRA Deemed University

---

## ⭐ If you found this project useful, consider giving it a star!
