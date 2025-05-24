# Breast_Cancer_Detection_Model
# 🧠 Breast Cancer Detection Model

![License](https://img.shields.io/github/license/haiderabbas678/Breast_Cancer_Detection_Model )
![Python](https://img.shields.io/badge/python-3.8+-blue.svg )
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-notebook-orange )

> A machine learning model to predict whether a breast tumor is malignant or benign using clinical data.

This project implements a **Breast Cancer Classification Model** using the **Wisconsin Breast Cancer Dataset** from Kaggle. It uses **Logistic Regression** to classify tumors as either **Benign (B)** or **Malignant (M)** based on 30 features extracted from digitized images of fine needle aspirates (FNA) of breast masses.

---

## 🔍 Features

✅ Automatic dataset download via Kaggle API  
✅ Data preprocessing and cleaning  
✅ Label encoding of diagnosis column  
✅ Train-test split and feature scaling  
✅ Logistic Regression classification  
✅ Model accuracy evaluation  

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `breast_cancer_prediction.ipynb` | Main Jupyter Notebook with full code and analysis |
| `README.md` | This documentation file |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/haiderabbas678/Breast_Cancer_Detection_Model.git 
cd Breast_Cancer_Detection_Model
```

### 2. Install Dependencies
```bash
pip install pandas numpy scikit-learn jupyter matplotlib seaborn kaggle
```

```Python
os.environ['KAGGLE_USERNAME'] = "your_username"
os.environ['KAGGLE_KEY'] = "your_api_key"
```
```bash
!kaggle datasets download -d uciml/breast-cancer-wisconsin-data
!unzip breast-cancer-wisconsin-data.zip
```

📊 ### Dataset
Name: Breast Cancer Wisconsin (Diagnostic) Dataset
Source: Kaggle
Description: This dataset contains 569 samples of breast cancer cell nuclei with 32 features extracted from digitized images.
Target Variable: diagnosis
M = Malignant (Cancerous) – 212 cases
B = Benign (Non-Cancerous) – 357 cases
🧾 Key Features:
Radius, Texture, Perimeter, Area, Smoothness
Compactness, Concavity, Concave Points
Symmetry, Fractal Dimension
(All measured as mean, standard error, and worst values)
🧹 Data Preprocessing:
Removed missing/unneeded columns: Unnamed: 32
Encoded diagnosis labels: M → 1, B → 0
Scaled features using StandardScaler
Split data: 75% training, 25% testing
🧪 Model Performance
Model Used: Logistic Regression
Evaluation Metrics:
Accuracy Score: 97.9%
Confusion Matrix:




