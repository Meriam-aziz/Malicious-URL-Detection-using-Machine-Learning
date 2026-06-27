# 🔒 Malicious URL Detection using Machine Learning

## 📌 Overview

This project presents a Machine Learning solution for detecting and classifying malicious URLs. It uses feature engineering techniques to extract meaningful characteristics from URLs and trains classification models to distinguish between malicious and legitimate websites.

---

## 🎯 Objective

The objective of this project is to build an accurate machine learning model capable of identifying malicious URLs and improving web security.

---

## 📊 Dataset

The project uses a dataset containing URLs labeled by their type (benign or malicious).

The dataset includes various URL patterns that are transformed into numerical features before model training.

---

## ⚙️ Workflow

1. Load the dataset.
2. Data cleaning and duplicate removal.
3. Feature engineering from URLs.
4. Data preprocessing and scaling.
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

### Random Forest Confusion Matrix

![Random Forest](images/random_forest_cm.png)

---

### Gradient Boosting Confusion Matrix

![Gradient Boosting](images/gradient_boosting_cm.png)

---

### Model Performance

![Performance](images/model_performance.png)

The models achieved strong performance in distinguishing malicious URLs from legitimate ones.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly
- tldextract

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
│   ├── random_forest_cm.png
│   ├── gradient_boosting_cm.png
│   └── model_performance.png
│
├── Malicious URLs.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Features

- URL feature engineering
- Data preprocessing
- Machine learning classification
- Performance evaluation
- Comparison between Random Forest and Gradient Boosting

---

## 👩‍💻 Author

**Meriam Aziz**

---

## ⭐ Future Improvements

- Deploy the model as a web application.
- Add real-time URL prediction.
- Improve feature extraction techniques.
- Experiment with Deep Learning models.
