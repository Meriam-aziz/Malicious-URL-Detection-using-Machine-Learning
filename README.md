# 🔒 Malicious URL Detection using Machine Learning

## 📌 Overview

This project presents a Machine Learning solution for detecting malicious URLs using feature engineering and classification algorithms. The system analyzes URL characteristics, extracts meaningful features, and classifies URLs as either malicious or legitimate.

---

## 🎯 Objective

The main objective of this project is to build an accurate machine learning model capable of detecting malicious URLs and improving cybersecurity by identifying potentially harmful websites.

---

## 📊 Dataset

The dataset contains URLs labeled as **Benign** or **Malicious**.

After preprocessing, several features were extracted from each URL to improve the performance of the machine learning models.

---

## ⚙️ Workflow

1. Load the dataset.
2. Data preprocessing and cleaning.
3. Feature extraction from URLs.
4. Exploratory Data Analysis (EDA).
5. Train Machine Learning models.
6. Evaluate model performance.
7. Compare classification results.

---

## 🤖 Models Used

- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📈 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report

---

## 🖼️ Results

### Dataset Distribution

![Dataset Distribution](images/dataset_distribution.png)

---

### Distribution of Malicious URLs by Region

![Malicious URLs by Region](images/malicious_urls_by_region.png)

---

### Random Forest Confusion Matrix

![Random Forest Confusion Matrix](images/random_forest_cm.png)

---

### Gradient Boosting Confusion Matrix

![Gradient Boosting Confusion Matrix](images/gradient_boosting_cm.png)

The trained models successfully classified malicious and legitimate URLs with high accuracy, demonstrating the effectiveness of machine learning techniques for cybersecurity applications.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn

---

## ▶️ How to Run

```bash
git clone https://github.com/Meriam-aziz/Malicious-URL-Detection-using-Machine-Learning.git

cd Malicious-URL-Detection-using-Machine-Learning

pip install -r requirements.txt

jupyter notebook "Malicious URLs.ipynb"
```

---

## 📁 Project Structure

```text
Malicious-URL-Detection-using-Machine-Learning/
│
├── images/
│   ├── dataset_distribution.png
│   ├── malicious_urls_by_region.png
│   ├── random_forest_cm.png
│   └── gradient_boosting_cm.png
│
├── Malicious URLs.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Features

- URL preprocessing and feature extraction.
- Exploratory Data Analysis (EDA).
- Machine Learning classification.
- Performance evaluation using confusion matrices.
- Comparison between Random Forest and Gradient Boosting models.

---

## 👩‍💻 Author

**Meriam Aziz**

---

## ⭐ Future Improvements

- Deploy the model as a web application using Streamlit or Flask.
- Add real-time URL prediction.
- Integrate additional URL-based security features.
- Explore Deep Learning approaches for malicious URL detection.
