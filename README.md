# 🔒 Malicious URL Detection using Machine Learning

A Machine Learning project that detects malicious URLs using feature engineering and supervised learning algorithms to improve cybersecurity and online safety.

---

## 📌 Overview

Malicious URLs are one of the most common attack vectors used in phishing, malware distribution, and online fraud. This project applies Machine Learning techniques to automatically classify URLs as malicious or legitimate based on extracted URL features.

The project covers the complete Machine Learning pipeline, including data preprocessing, feature engineering, exploratory data analysis (EDA), model training, evaluation, and performance comparison.

---

## 🚀 Features

- URL preprocessing and cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning classification
- Model comparison
- Performance evaluation
- Confusion Matrix visualization
- Cybersecurity-focused prediction system

---

## 📊 Dataset

The dataset contains labeled URLs that were processed and transformed into meaningful numerical features before training.

### Data Processing

- Data Cleaning
- Feature Extraction
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Train/Test Split

---

## 🤖 Machine Learning Models

The following models were implemented and evaluated:

- 🌲 Random Forest Classifier
- 📈 Gradient Boosting Classifier

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Random Forest | **97%** |
| Gradient Boosting | **95%** |

Random Forest achieved the highest accuracy and demonstrated the best overall performance for malicious URL classification.

---

## 📷 Results

### Dataset Distribution

<p align="center">
  <img src="images/dataset_distribution.png.png" width="700">
</p>

---

### Distribution of Malicious URLs by Region

<p align="center">
  <img src="images/malicious_urls_by_region.png.png" width="700">
</p>

---

### Random Forest Confusion Matrix

<p align="center">
  <img src="images/random_forest.png.png" width="550">
</p>

---

### Gradient Boosting Confusion Matrix

<p align="center">
  <img src="images/gradient_boosting.png.png" width="550">
</p>

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix

Random Forest achieved the best classification performance among the evaluated models.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Plotly
- Jupyter Notebook

---

## 📂 Project Structure

```text
Malicious-URL-Detection-using-Machine-Learning/
│
├── images/
│   ├── dataset_distribution.png.png
│   ├── malicious_urls_by_region.png.png
│   ├── random_forest.png.png
│   └── gradient_boosting.png.png
│
├── Malicious URLs.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

```bash
git clone https://github.com/Meriam-aziz/Malicious-URL-Detection-using-Machine-Learning.git

cd Malicious-URL-Detection-using-Machine-Learning

pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
jupyter notebook "Malicious URLs.ipynb"
```

---

## 💡 Future Improvements

- Deploy the model using Streamlit or Flask
- Support real-time URL prediction
- Improve feature engineering techniques
- Explore Deep Learning approaches
- Build a REST API for deployment

---

## 👩‍💻 Author

**Meriam Aziz**

Artificial Intelligence Engineer

If you found this project useful, don't forget to ⭐ the repository.
- Add real-time URL prediction.
- Improve feature extraction techniques.
- Explore Deep Learning approaches for malicious URL detection.

