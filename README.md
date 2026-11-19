# 🧠 Brain Tumor Classification Using Deep Learning

**AI 342 – Deep Learning Course Project**

## 📌 Project Overview

This project focuses on classifying brain MRI images into four categories using Deep Learning and Machine Learning techniques.

The goal is to compare different classification approaches and evaluate their performance on brain tumor MRI images.

### 🎯 Classification Classes

- Glioma
- Meningioma
- Pituitary
- No Tumor

## 🧠 Models Implemented

Four models were implemented and compared:

1. **Custom CNN** – A Convolutional Neural Network built from scratch.
2. **ResNet-18** – Transfer Learning using a pretrained ResNet-18 model.
3. **Logistic Regression** – A traditional Machine Learning baseline.
4. **Support Vector Machine (SVM)** – An RBF-kernel classifier.

## ⚙️ Data Preprocessing

The project includes:

- Image resizing to 224 × 224 pixels.
- Normalization.
- Data augmentation using random horizontal flipping and rotation.
- Brightness and contrast adjustments.
- Training, validation, and testing splits.

## 📊 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

A comparison summary is generated to evaluate the performance of all four models.

## 🔍 Model Explainability

**Grad-CAM (Gradient-weighted Class Activation Mapping)** is implemented to visualize the important image regions influencing the Custom CNN's predictions.

The project also includes misclassification analysis to inspect incorrectly classified images.

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn
- OpenCV
- Google Colab

## 📂 Dataset

The project uses a Brain MRI dataset obtained from Kaggle.

The dataset should be organized as follows:

```text
Dataset/
│
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
│
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── notumor/
    └── pituitary/
```

The dataset is not included in this repository due to its size.

## 🚀 How to Run

1. Open the notebook using Google Colab.
2. Install the required dependencies.
3. Upload the dataset to Google Drive.
4. Mount Google Drive in Colab.
5. Update `DRIVE_DATASET_PATH` in the notebook to match your dataset location.
6. Run the notebook cells sequentially.

## 📁 Repository Contents

- `Brain_Tumor_Classification.ipynb` – Main project notebook.

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis.

## 👩‍💻 Author

**Jana Medhat**

Artificial Intelligence Student

