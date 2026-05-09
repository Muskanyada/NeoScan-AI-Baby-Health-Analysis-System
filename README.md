# NeoScan AI – Baby Health Analysis System

## 📌 Overview

NeoScan AI is an AI-powered healthcare system designed to detect whether a newborn baby is **normal or abnormal** using **Machine Learning** and **Computer Vision** techniques.
The system analyzes multiple visual indicators such as:

* 👶 Skin condition analysis
* 👁 Eye classification
* 😊 Facial feature detection
* 🧍 Full-body pose estimation

The project aims to support **early-stage infant health assessment** through automated image-based analysis using Deep Learning models.


# 🚀 Features

* Skin abnormality detection using deep learning
* Eye classification and analysis
* Facial feature-based health prediction
* Full-body pose estimation for posture analysis
* AI-based normal vs abnormal infant classification
* Image preprocessing and feature extraction pipelines
* Model training and evaluation support


# 🧠 Deep Learning Models Used

| Module             | Model Used                      |
| ------------------ | ------------------------------- |
| Skin Analysis      | EfficientNet-B3                 |
| Face Analysis      | VGG16, Vision Transformer (ViT) |
| Eye Classification | ResNet50, DenseNet121           |
| Full Body Pose     | ResNet-50                       |



# 🛠 Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* Scikit-learn
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook



# 📂 Project Structure

```bash
NeoScan-AI/
│
├── datasets/
│   ├── skin_dataset/
│   ├── eye_dataset/
│   ├── face_dataset/
│   └── pose_dataset/
│
├── models/
│   ├── EfficientNetB3/
│   ├── ResNet50/
│   ├── DenseNet121/
│   ├── VGG16/
│   └── ViT/
│
├── notebooks/
│   ├── skin_module.ipynb
│   ├── eye_module.ipynb
│   ├── face_module.ipynb
│   └── full_body_module.ipynb
│
├── results/
│
├── requirements.txt
│
└── README.md
```



# ⚙️ Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Muskanyada/NeoScan-AI-Baby-Health-Analysis-System.git
```

---

## 2️⃣ Navigate to Project Directory

```bash
cd NeoScan-AI-Baby-Health-Analysis-System
```

---

## 3️⃣ Create Virtual Environment (Recommended)

### For Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### For Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```


# ▶️ How to Run the Project

## Run Google collab

```bash
Google collab
```

Then open the required module notebook:

* `skin_module.ipynb`
* `eye_module.ipynb`
* `face_module.ipynb`
* `full_body_module.ipynb`


# 📊 Workflow

1. Image Dataset Collection
2. Data Preprocessing
3. Feature Extraction
4. Model Training
5. Classification & Prediction
6. Performance Evaluation


# 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix


# 🎯 Future Improvements

* Real-time infant monitoring system
* Mobile application integration
* Deployment using Flask/Streamlit
* Cloud-based healthcare dashboard
* Multi-disease infant diagnosis support



# 📜 License

This project is developed for educational and research purposes.

